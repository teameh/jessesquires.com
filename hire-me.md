---
layout: standalone
title: Hire Me
---

Need an iOS developer? Look no further! I am available for hire for freelance and contract work for iOS. If you don't know much about me, take a look around this site to learn more. While my availability varies, I can usually work a maximum of 15-30 hours per week on any given project. I am not pursuing full-time employment at this time.

<div class="d-block bg-light px-4 pt-3 my-4 border rounded" markdown="1">
**If you are interested in working together, you can [contact me here]({% link contact.md %}).** I typically get booked quickly, so I recommend reaching out sooner rather than later. Please be as detailed as possible about your project and what you are looking for.
</div>

### Testimonials

I've worked at a number of different companies as a full-time software engineer, as well as an independent contractor. With [nearly a decade of experience]({% link linkedout.md %}), I've worked with a lot of great folks over the years. Here's what a few of them have to say.

<ul class="list-unstyled">
{% for each in site.data.testimonials %}
    <li>
        <p>
            <i class="bi bi-star-fill text-secondary"></i>
            <b><a href="{{ each.link }}">{{ each.name }}</a></b> &mdash; <i>{{ each.company }}</i>, {{ each.year }}
            <br/>
            <span class="fw-light">{{ each.position }}</span>
        </p>
        <blockquote>"{{ each.testimonial }}"</blockquote>
    </li>
{% endfor %}
</ul>
