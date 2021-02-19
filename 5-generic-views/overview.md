# Title

Using generic views in Django

## Role(s)

- student
- developer

## Level

- intermediate

## Product(s)

- Django
- Azure App Services
- Visual Studio Code

## Prerequisites

- HTML/CSS
- Git
- npm
- Python

## Summary

Because Django was designed for data-driven applications it includes numerous built-in utilities to streamline the amount of code needed. One key area where Django makes a developer's life easier is by providing generic views, which are pre-built with all the necessary code to perform core operations like displaying and editing data. We will see how we can use generic views to greatly reduce the amount of code required.

## Learning objectives

1. Displaying data
2. Editing data
3. Improving form display

## Chunk your content into subtasks

Identify the subtasks of *module title*

| Subtask | What part of the introduction scenario does this subtask satisfy? | How will you assess it: **Exercise or Knowledge check**? | Which learning objective(s) does this help meet? | Does the subtask have enough learning content to justify an entire unit? If not, which other subtask will you combine it with? |
| ---- | ---- | ---- | ---- | ---- |
| Using generic views to display data | Displaying data | Exercise | Displaying data | yes |
| Using generic views to edit data | Editing data | Exercise | Editing data | Yes |
| Using crispy-forms to improve data display | Improving form display | Exercise | Improving form display | yes |

## Outline the units

1. **Introduction to the Django admin site**

    The Django admin site is a powerful utility for allowing business users to modify data. Django includes all the necessary tools for creating users and managing permissions.

1. **Exercise - Obtain the starter**

    To streamline this module, we provided a starter project you can use.

    1. Cloning the repository
    2. Installing the necessary libraries
    3. Open Visual Studio Code

1. **Using generic views to display data**

    Displaying data in a data-driven website involves quite a bit of boiler-plate code. We explore how we can use generic views to abstract away the code.

    - Detail view
    - List view

1. **Exercise - Implementing generic views to display data**

    We will see how to use a generic view to create a detail page

    - Create the view
    - Register the view
    - Test the page

    1. Create the view
    2. Register the view
    3. Test the page

1. **Using generic views to edit data**

    Editing data through a website is deceptively complex. We will see how we can use generic views to manage the workflow, allowing us to focus on our application.

    - The edit workflow
    - How edit views work
    - Necessary updates

1. **Exercise - Implementing generic views to edit data**

    Let's see how we can use generic views to create new items.

    - Necessary updates
    - Creating the view
    - Registering the view
    - Testing the page

    1. Update the model
    2. Create the view
    3. Register the view
    4. Test the page

1. **Using django-crispy-forms to improve the display**

    By default, the forms generated by generic views are regular forms. We will see how we can use a library to improve the display of our forms.

1. **Exercise - Implementing django-crispy-forms**

    Let's close by implementing django-crispy-forms

    - Install the library
    - Implement the library

    1. Installation
    2. Registration
    3. Updating the template
    4. Testing the site

1. **Summary**

    We explored how Django's generic forms allow us to streamline the necessary code for our site.

1. **Knowledge check**

    What types of questions will test *learning objective*? *[(Knowledge check guidance)](https://review.docs.microsoft.com/learn-docs/docs/id-guidance-knowledge-check)*

    - Multiple choice

## Notes

Note any additional information that may be beneficial to this content such as links, reference material, etc.

- [Django](https://docs.djangoproject.com/)