# Haste Interactive

![Yellow clock seemingly moving but static](https://i.imgur.com/FeNzLre.png)

`realtime feature flag detection`

haste/
- `flash-sync` - A library for enabling real time communication, notably real time chat. 
- `flash-media` - A managed api for uploading images and video and then streaming it.
- `flash-auth` - First library I am building is a redis auth and validation server, the idea to auth against the login system for the non cached request, but from then on, instead of making a request it pulls straight from redis.
- `flash-hooks`: A web hooks hosting platform and polyfill strategy for ensuring edge compatible hooks
- `flash-guard` - Role Based Access, Management, and Security
- `flash-flags` - A library for utilizing, managing and creating feature flags to ensure the safety of the
- `flash-shard` - A library for segmenting user accounts for AB testing and gradual release
- `flash-cms` - A library to enable support for real time updates and edits on the CMS.
- `flash-forms`: A state management and validation library with composable types and compatible with forms. ?optional continuation of [react-validation-strategy](https://github.com/codymurphyjones/react-validation-strategy)

**Webhooks:**
- https://zapier.com/engineering/static-webhooks/
- https://docs.webhookthing.com/ (do not steal from theo)
- Real time webhook updates

**Goals**
- https://vercel.com/docs/workflow-collaboration/draft-mode
- https://www.sanity.io/docs/content-source-maps
- https://www.sanity.io/docs/vercel-visual-editing
- https://vercel.com/docs/workflow-collaboration/comments
- https://www.youtube.com/watch?v=xzaoJ5JQP0U

Highlevel Roadmap:

Haste Interactive is setting the stage for real-time communication and application development utility, starting with the foundational real-time communication module, `flash-sync`. This library handles data transmission workloads across the entire system, acting as the backbone of real-time interaction within applications. Simultaneously, `flash-media` addresses the need for media uploads, a common functional requirement for web and mobile apps. It handles uploading, storing, and retrieving media files and ensures cross-platform performance by converting files to universally compatible formats.

The innovative `flash-auth` library validates authentication instantly, offering insights into active users and their connections. It also actively monitors users, notifying the system when they disconnect or become inactive. Coupled with this real-time responsiveness is `flash-hooks`, which creates a simple workflow for interacting with your app via real-time messaging from hooks API calls. This feature adds a new layer of interaction, broadening the possibilities of how apps can connect and respond to users.

Security and control are addressed through `flash-guard`, a comprehensive tool for role-based access, management, and security. This module assists in protecting routes, actions, and user data, providing an essential layer of security. Building on top of this is `flash-flags`, a feature flag system that ensures real-time updates connected to flag changes. This system enhances the control over new feature releases, offering a layer of safety and flexibility.

For more tailored user experiences, `flash-shard` provides an interface for segmenting user accounts, enabling nuanced A/B testing and support for gradual releases. This functionality helps in creating more personalized user journeys and controlled experimentation. In addition, `flash-cms` brings the power of real-time editing to your content management system. It allows authorized users to edit and share changes to content in real time, without the need for deployment steps. Platforms like sanity and builder.io are supported initially, enabling streamlined content creation and management.

Overall, Haste Interactive integrates a wide range of functionalities into one cohesive platform. Whether you're building real-time chat applications, managing media content, or rolling out new features securely, the suite of libraries in Haste Interactive provides the tools needed to innovate, secure, and engage with your audience like never before.

#### Landing Page Details
- https://www.framer.com/motion/scroll-animations/
- https://www.i18next.com/
- https://hackernoon.com/does-your-saas-have-a-positioning-or-messaging-problem?source=rss
- https://uxplanet.org/design-an-incredible-landing-page-in-a-few-simple-steps-87f6bfb4bbf9



#### UX Principles
- https://www.infoworld.com/article/3690150/optimizing-video-for-ux-what-a-developer-needs-to-know.html#tk.rss_all
- https://getmcss.com/press/ux-design-principles-native-apps
- https://itnext.io/ui-the-interface-should-not-be-distracting-75457848bceb

##### UX Audit: 
https://www.wpbeginner.com/beginners-guide/how-to-do-a-ux-audit-of-your-wordpress-site/

### Design Rules
- Use space to group related elements
- Be consistent
- Ensure similar looking elements function similarly
- Create a clear visual hierarchy
- Remove unnecessary styles
- Use colour purposefully
- Ensure interface elements have a 3:1 contrast ratio
- Ensure text has a 4.5:1 contrast ratio
- Don’t rely on colour alone as an indicator
- Use a single sans serif typeface
- Use a typeface with taller lower case letters
- Limit the use of uppercaseUse regular and bold font weights only
- Avoid pure black text
- Left align text
- Use at least 1.5 line height for body text

##### Typescale 18px body, 14px small, 32px title

`Color Rule: 60 | 30 | 10`

- Visual Hierarchy
- Contrast
- Balance
- Consistency
- Simplicity
- Feedback


Animation:
- https://blog.bitsrc.io/component-driven-development-and-composable-applications-a-guide-7a0934e60936
- https://github.com/motion-canvas/motion-canvas


**Laws of UX**

https://uxplanet.org/laws-of-ux-that-airbnb-follows-99427770ed0c


In an ever-evolving field like software development, it's crucial to understand current practices. This post is based on a comprehensive study where we analyzed over a million Git commits.

Rather than making predictions, we've dived into the hard data. We've uncovered actual trends based on real-world Git use.

In this post, I will unpack key findings from our analysis. 

So, let's start.

1. Focus on Product Growth and Quality Maintenance
2. Role of Collaboration in Successful Repositories
3. Trends in Communication: From Pull Requests to Bug Fixes
4. Analyzing the Frequency and Impact of Refactoring
5. The Efficacy of Git Blame in Software Development  


- React-Native-Skia
- https://reactnative.dev/docs/accessibility.html
- https://nextui.org/docs/components/

**User Experience**
- https://hackernoon.com/63-stories-to-learn-about-accessibility?source=rss


**Analytic Dashboard:**

https://www.react-graph-gallery.com/

https://formidable.com/open-source/victory/


**Interactions**

https://www.youtube.com/watch?v=a5SgLyfiDnU

**XState:** 

https://slack.engineering/real-time-messaging/
https://www.youtube.com/watch?v=3wZBSeLxVEw

Micro Front Ends:
https://blog.bitsrc.io/creating-seamless-user-experiences-a-comprehensive-guide-to-micro-frontend-architectural-patterns-9118a70386b7


Landing Page    
https://www.algolia.com/blog/ecommerce/top-features-of-successful-b2b-ecommerce-websites/

https://www.getwaitlist.com/


**Inspiration**

https://formidable.com/

