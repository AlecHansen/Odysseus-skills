---
name: create-generic-lesson-plan
description: 'Create clear, practical, and realistic lesson plans across subjects.'
---

# Create Generic Lesson Plan

## Primary Directive

If there are points in formatting rules or output structure, write them as bullet points in your output.
Follow the output structure exactly unless you need to adapt timing or something similar.
Do not use slanted text.

Your goal is to create a clear, practical, realistic, and structured lesson plan for `${input:PlanPurpose}`.

The lesson plan must be easy for a teacher to understand, adapt, and use in a real classroom.

The response must avoid vague teaching language and must focus on concrete actions, realistic timing, student activity, teacher support, differentiation, and assessment during the lesson.

## Execution Content

This skill is designed to create general lesson plans across subjects.

Use this skill when the user asks for:

  - a single lesson
  - a double lesson
  - a weekly plan
  - a unit plan
  - a classroom activity
  - group work
  - station-based learning
  - a revision lesson
  - an introductory lesson
  - a practical lesson
  - an outdoor lesson
  - an assessment activity

Use this skill as a general base skill. More specific subject skills can build on top of this skill.

## Core Requirements

  - Create lesson plans that are practical to use in a real classroom.
  - Use clear headings, short sections, tables, and bullet points.
  - Keep the plan realistic for the given time frame.
  - Include what the teacher does and what the students do.
  - Include student activity, not only teacher explanation.
  - Include differentiation for different student needs.
  - Include simple assessment during the lesson.
  - Include a clear beginning, middle, and ending.
  - Avoid unnecessary theory unless the user asks for it.
  - Do not create too many learning objectives.
  - Do not overload the lesson plan with too many activities.

## Input Handling

If the user provides specific details, use them actively.

Relevant details may include:

  - subject
  - grade level
  - student age
  - duration
  - topic
  - learning objectives
  - available materials
  - digital tools
  - student needs
  - class size
  - assessment type
  - teaching method
  - language
  - curriculum goals or curriculum requirements

If the user gives little information, make reasonable assumptions and state them briefly.

Do not stop the response with many follow-up questions unless the request is impossible.

Example assumption:

"I assume this is a 45-minute lesson for lower secondary students. The plan can be adjusted."

## Lesson Design Principles

### Make the plan easy to follow

The teacher should quickly understand:

  - what the lesson is about
  - what the students should learn
  - what needs to be prepared
  - what happens step by step
  - how the lesson can be adapted

### Keep the lesson realistic

Do not include too many activities.

For a 45-minute lesson, preferably use:

  - 10 minutes for introduction and overview of what will happen in the lesson
  - 10 minutes for modelling or a shared example
  - 20 minutes for student activity
  - 5 minutes for summary and assessment

For longer lessons, add more time for exploration, collaboration, sharing, and student reflection.

### Start simple

Begin with something the students can understand quickly.

Useful starts include:

  - an open question
  - an image
  - a short discussion
  - a concrete example
  - a simple demonstration
  - a quick task
  - a situation the students recognize

### Model before independent work

If students are doing something new, the teacher should model it first.

The teacher can use phrases such as:

  - "First, I look for..."
  - "Here, I choose to..."
  - "I can check whether this is correct by..."
  - "Now I try a different strategy..."

### Make students active

A good lesson plan should include:

  - a clear start
  - short teacher input
  - a clear task
  - student work
  - teacher guidance
  - shared summary

Avoid lesson plans where the teacher talks for most of the lesson.

### Make the activities concrete

Avoid vague wording such as:

"Students work with the topic."

Use concrete wording such as:

"Students work in pairs. First, they solve tasks 1-3 together. Then they choose one answer or one solution to explain to another pair."

### Include student thinking

The plan should encourage students to:

  - explain
  - justify
  - explore
  - compare
  - test
  - improve
  - collaborate
  - reflect

## Formatting Rules

Use clean and simple Markdown formatting.

## Mandatory Output Structure

Use this structure unless the user asks for another format.

# Lesson Plan: [Title]

## Quick Overview

  - Subject/area: [Subject or general area]
  - Grade/level: [Grade, age group, or level]
  - Duration: [Lesson duration]
  - Topic: [Topic]
  - Lesson goal: [Main purpose of the lesson]
  - Materials/resources: [Materials, tools, worksheets, or digital resources]

## Assumption

State what assumptions have been made because the user did not provide enough information.

If no assumptions are needed, write:

"No major assumptions are needed."

## Learning Objectives

Students will be able to:

  - [Learning objective 1]
  - [Learning objective 2]
  - [Learning objective 3]

Use 2-4 learning objectives.

The objectives must be concrete and understandable for both teachers and students.

## Before the Lesson

The teacher should prepare:

  - [Preparation 1]
  - [Preparation 2]
  - [Preparation 3]

## Lesson Sequence

| Time | Part | What happens? | Teacher's role | Students' role |
|---|---|---|---|---|
| 0-10 min | Introduction | [What happens] | [Teacher action] | [Student action] |
| 10-20 min | Modelling/shared example | [What happens] | [Teacher action] | [Student action] |
| 20-40 min | Main activity | [What happens] | [Teacher action] | [Student action] |
| 40-45 min | Summary | [What happens] | [Teacher action] | [Student action] |

Adjust the timing so it fits the duration of the lesson.

## Main Activity

Students will:

  - [Step 1]
  - [Step 2]
  - [Step 3]

The teacher should look for:

  - [What should be observed]
  - [Common difficulty]
  - [Signs of understanding]

The teacher can support students by:

  - [Support strategy 1]
  - [Support strategy 2]
  - [Support strategy 3]

## Questions the Teacher Can Ask

Use 4-8 questions or create similar ones:

  - What do you notice?
  - How did you figure that out?
  - Can you explain it in another way?
  - What happens if we change something?
  - What are you sure about?
  - What are you unsure about?
  - Which strategy did you use?
  - What would you do differently next time?

Adapt the questions to the actual topic of the lesson.

## Differentiation

### More Support

  - [Support option 1]
  - [Support option 2]
  - [Support option 3]

### Expected Level

  - [Task at expected level 1]
  - [Task at expected level 2]
  - [Task at expected level 3]

## Assessment During the Lesson

The teacher can assess learning through:

  - [Observation point]
  - [Question or discussion]
  - [Small product, answer, explanation, or exit ticket]

Keep the assessment practical and connected to the learning objectives and lesson structure.

## Ending the Lesson

End the lesson by:

  - [Ending activity]
  - [Reflection question]
  - [Connection to the next lesson]

## Follow-Up Work

Possible next steps:

  - [Follow-up idea 1]
  - [Follow-up idea 2]
  - [Follow-up idea 3]

## Quality Rules

Before finalizing the lesson plan, check that it has:

  - a clear topic
  - appropriate grade level
  - realistic timing
  - concrete activities
  - clear teacher role
  - clear student role
  - differentiation
  - assessment during the lesson
  - a simple ending
  - no unnecessary filler text

Before finalizing the lesson plan, check that:

  - Use a table for the lesson sequence.
  - Keep table cells short and tidy.
  - Do not write long paragraphs in the table.
  - Do not use italic text.
  - Do not use `*text*` or `_text_`.
  - Do not use bullet points inside the table.
  - Add details below the table instead if something needs more explanation.
  - Check that the table has the same number of columns in each row.

If something is missing, add it before giving the final response.

## Avoid

Avoid:

  - lesson plans that are too long
  - too many learning objectives
  - unclear activities
  - generic teaching phrases
  - unrealistic timing
  - lesson plans where the teacher does all the work
  - assessment that takes over the lesson
  - too many tools or materials at once
  - activities that do not connect to the goal of the lesson
  - academic language that does not help the teacher
