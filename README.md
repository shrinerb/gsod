# Google Season of Docs Project Ideas

We are really excited to be a part of Google Season of Docs and look forward to collaborating with technical writers to improve our documentation. 

## About Shrine

Shrine is a Ruby library (a Ruby library is called a gem) used in Ruby web applications to handle file uploads and manage the file in the application. Shrine was created by @janko to address various issues in the other file attachment gems and you can read about it in his [announcement of Shrine](https://twin.github.io/introducing-shrine/). We are a small team of 3 that maintain and support Shrine.

## For Students

Please familarize yourself with the [technical writer guide](https://developers.google.com/season-of-docs/docs/tech-writer-guide) for GSoD.

Proposals should include the project idea (see [idea list](#project-ideas) below), scope, breakdown of timeline, and answers to our questions listed in the [Student Application Guide](#student-application-guideline) below.

We are open to hearing your feedback and ideas as well.

### Some context

The main Shrine project is located in the [Shrinerb/shrine repo](https://github.com/shrinerb/shrine). It has a base and 50+ plugins that a user can add to the base to reconfigure it to do anything from direct file uploads, background processing, add metadata, and many other things needed or combination of it. We also have demo applications so users can see a working implementation of it.

We've done our best in documenting the gem, providing how-to guides, the design of shrine, code samples, etc. We have the following documentation:

1. [Readme](https://github.com/shrinerb/shrine/blob/master/README.md) in the main project
2. [Guides](https://github.com/shrinerb/shrine/tree/master/doc) files in base `/doc` folder
3. [Plugin documentation](https://github.com/shrinerb/shrine/tree/master/doc/plugins)
4. [Reference list](https://shrinerb.com) of guides, plugins, articles, demos, etc
5. [Wiki](https://github.com/shrinerb/shrine/wiki) which has information on how 3rd party clients are used to interface with Shrine on server

### Project Ideas

When it comes to documenting, one of the big challenges of Shrine is a result of its modularity and large number of plugins which allow it to work across a vast number of applications and situations. When a new developer comes across Shrine, it can be overwhelming to understand how it works, whether it is the right solution for them, and how to piece something together using a set of plugins for their application. Also for some one who has used Shrine before, they may run into issues on how to implement something and not able to find it in the docs or missed it or understood it differently. We've worked hard over the years to reduce these situations. With that said, we welcome the opportunity to work with you (technical writers) to see how we can further improve our documentation.

Some project ideas are:

1. Refactor the existing documentation to provide an improved user experience and a more accessible information architecture. (This can be in terms of overall structure, templates, actual sample documentation, or the whole thing)
2. Improve any one or more of the following: readme, guides, plugin documentation, reference list, and Wiki.
3. Feel free to propose your own idea and scope of project that you'd like to work on that will improve the documentation for Shrine.

If you have questions, you can reach us through the [Ruby-shrine Google group](https://groups.google.com/forum/#!forum/ruby-shrine) or contact @hmistry.

### Student Application Guideline

We would like to see the following questions answered in your student application:

1. **Contact information.** Please provide your email address, GitHub username, and general city + country location (for privacy reasons no address).

2. What project do you want to work on? This can be a project that you came up with yourself, a project that you collaborated with a project maintainer or possible GSoD mentor with, or a project that you chose from the ideas list.

3. Describe your relevant educational/professional background, including school, major, publications, etc.

4. Describe your experience with the following: programming languages, markdown, documentation tools, Github Pages, creating websites, documentation for API's, libraries, etc. (No experience is okay! We use this to evaluate projects and mentors for a good fit.)

5. Have you contributed to any open source projects? Code or documentation patches are both useful! Please provide links.

6. What other commitments do you have during GSoD? What obstacles do you foresee that may affect you contributing during the GSoD period?

7. What are you looking to get out of GSoD and/or working on your proposed project?

8. Please provide your expected timeline for your project, from application until pencils-down. What intermediate milestones will you set for yourself? The greater the detail on this question, the better.

9. What are your hobbies, aside from coding? Tell us a little about yourself that isn't reflected in the rest of your application.

10. What else do you think we should have asked but didn't? Propose a question of your own and answer it here.

Bonus question: How do you think we can get more non-programmers like designers, tech writers, project managers interested in open source software development?
