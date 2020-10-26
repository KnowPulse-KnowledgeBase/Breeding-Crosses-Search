---
layout: lesson
root: .
# Overall title for the Lesson.
# This should be in the form of a question if possible.
title: "Use germplasm search to find parents for a crossing block"

# Single Sentence purpose for this lesson.
short-purpose: "This lesson will show you how to trace back parental information for an individual cross"

# Single-Sentence describing the researchers
# who will be helped by this tutorial.
who: "Pulse Crop Researchers focused on variation data."

# A comma-separated list of maintainers for this lesson.
maintainers: "Lacey-Anne Sanderson, Ruobin Liu"

# A short paragraph describing why we created this lesson.
# What question is it trying to solve and why is that question important.
why: "Pulse Crop Researches may feel frustrated when they cannot recall the name or parental information of a cross. This lesson tries to solve this problem by showing our researchers how to find parents for a crossing block. "

# A short list of items researchers will learn in this lesson.
learn:
- "How to use Breeding Cross Search"


data-description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lacinia orci risus. Quisque condimentum nunc posuere, rutrum nunc eu, cursus enim. Nam sit amet turpis sit amet erat pulvinar consequat eget ac erat. Aliquam erat volutpat. Aenean in bibendum nibh. Proin iaculis dictum augue nec faucibus. Integer et arcu tortor. Donec at tristique eros. Integer consequat aliquet mauris, vitae imperdiet orci iaculis sit amet. Cras sit amet mollis lacus. Sed ac auctor mi, sit amet laoreet tellus. Vivamus vehicula congue velit. Cras vulputate est nec velit pretium condimentum. Vivamus eu leo sed est ullamcorper tincidunt at non dolor. Duis vestibulum pellentesque felis, at aliquam risus condimentum at."
---

The KnowPulse KnowledgeBase focuses on short question-based lessons to help researchers get their work done.

- **Purpose:** {{ page.short-purpose }}
- **Who:** {{ page.who }}
- **Maintainer(s):** {{ page.maintainers }}

{{ page.why }}

<strong>Some of the things you will learn include:</strong>
<ul>
	{% for item in page.learn %}
	<li style="font-weight:bold">{{ item|markdownify }}</li>
	{% endfor %}
</ul>

> ## Getting Started
>
> The KnowPulse KnowledgeBase lessons are hands-on, so participants are
> encouraged to use their own computers to ensure the proper setup of tools
> for an efficient workflow. To most effectively use these materials,
> please make sure to download the data and install everything before
> working through this lesson.
>
> This workshop assumes no prior experience with the tools covered in the
> workshop.
>
> To get started, follow the directions in the [Setup](setup.html) tab to
> get access to the required software and data for this workshop.
{: .prereq}


> ## Data
>
> {{ page.data-description }}
{: .prereq}
