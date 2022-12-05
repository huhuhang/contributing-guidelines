# Formatting and Design Guide

This guide is intended to help you write and design documentation that is clear, concise, and consistent.

## Markdown

1. You must use Markdown to write labs, challenges, and solutions. Learn more about Basic writing and formatting syntax [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
2. All markdown files should be formatted with [Prettier](https://prettier.io/).
3. All markdown titles should use the [title case](https://en.wikipedia.org/wiki/Title_case) format. You can use the [titlecase converter](https://titlecaseconverter.com/).
4. All labs and challenges should have a `## Skills` section that lists the skills that are covered in the lab or challenge.
   - The skills should be listed as an unordered list.
   - The skills should be linked to the skill tree.
   - The skills should be in the title case.
5. All proper nouns should use official usage.
   - For example, GitHub instead of Github.
   - For example, Python instead of python.
6. Single backticks can only be used for inline code. It can not be used for highlighting a word or phrase.
   - For example, `print("Hello World")`.
7. Double backticks can only be used for code blocks. It must have a language specified.
8. Grammarly should be used to check for spelling and grammar errors.

## Images

1. All images should not infringe on any copyright or trademark laws.
2. All images should be in the `assets` directory.
3. All images should be compressed using [TinyPNG](https://tinypng.com/) before being added to the repository.
4. All images should be named using the following format: `lab-<lab-name>-<step-number>-<image-number>.png`.
5. All images should be referenced using the following format: `![<image-description>](assets/lab-<lab-name>-<step-number>-<image-number>.png)`.

## Style

Below, you’ll find a list of recommendations and best practices for making great scenarios:

- Keep titles and descriptions succinct.
- Include an Intro - Set the stage and let learners know what to expect
- Include a "Lessons Learned" page at the end to summarize what the learners should have picked up
- Give credit where credit is due - did you use an image or idea from someone else? Let the learners know.
- Add complicated software set-ups to the image itself - avoid asking users to install software after they launch
- Aim to keep your Kubernetes and Ubuntu scenarios running at or under 4CPUs and 4GB of Memory
- Keep your instructions simple to avoid taking up precious space. For example, we recommend:

Take a look at the YAML files that define this application.

```bash
cat echoserver.yaml
```

instead of:

In the next step, you will see there is a YAML file that defines this application. Click on or type this command to see the YAML file.

```bash
cat echoserver.yaml
```

via. [Katacoda Formatting and Design Guide](https://www.katacoda.community/essentials/formatting.html).
