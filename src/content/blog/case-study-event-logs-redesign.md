---
title: "UX/UI Case Study: Waypoint Logs Page Redesign"
description: "Developed an event logs page for the enterprise application, Waypoint, aiming to enhance findability and readability to aid users in evaluating application performance."
pubDate: "Aug 10 2023"
heroImage: "/public/EventLogs-MilitaryMockup.avif"
---

<style>
  p{
    margin-bottom:2rem;
  }
    ul li::marker{
       color:#754d18; 
    }
img {
    border-radius:4px;
    /* filter: drop-shadow(0px 4px 5px #1C25204D); */
}
</style>

# Project Background
<!-- - Developed an event logs page for the enterprise application, Waypoint, aiming to enhance findability and readability to aid users in evaluating application performance.
- Addressed issues with event logs to uncover unnoticed bugs and improve user experience. -->
**Goals**: Attain deep insights into Waypoint's functionality and areas needing improvement, enabling swift and strategic platform-wide adjustments. This initiative will significantly enhance our business-to-customer relationship, bolstering client trust and confidence in our services.
<br>**Project significance**: Resolving historical lack of evidence for reported issues, fostering a more proactive approach to resolving client concerns.
<br>**Target Audience**: SaaS business and software development managers.
<br>**Client’s Industry**: Government-focused, Large Scale Scrum software as a service business.
<br>**Time**: 1 two-week sprint

# Research Phase
- Conducted Usability Testing
    - Discovered challenges: Incomplete data, disorganized logs, data readability, navigation difficulties (findability).
    - Task completion involved log finding, accessing logs belonging to groups, date range filtering, sharing logs, and comprehension of log messages. 
- Dot Voting
    - Confirmed user preference for the location of a section related to the event log feature. 
    - Users prefered the features in seperate pages, but as neighbors in the sitemap with links allowing one to jump from one area to another as both features required plenty of real estate and users mentioned how they'd likely want to bookmark both in their browsers.

[![Redesigned Event Logs Page](/212-RMO-BeforeTest-EventLogsPage.avif)](/212-RMO-BeforeTest-EventLogsPage.avif)
[![Redesigned Event Logs Page](/212-RMO-EventLogsPage-DotVoting-01.avif)](/212-RMO-EventLogsPage-DotVoting-01.avif)

# Design Process
- The process involved user flow analysis, usability testing, wireframing, dot voting, high fidelity designs, additional usability testing.
- Continuous iterations based on user feedback and usability testing results.
- User feedback led to the inclusion of progressive disclosure in filters, access to multiple filters at once, and a collapsible sidebar for filter management to achieve all of that cleanly.

View the original design and redesign below. For more images of the design, visit

[![Usability test findings on the Event Logs page before it's redesign](/212-RMO-EventLogsPage-OldDesign-01.avif)](../../../public/212-RMO-EventLogsPage-OldDesign-01.avif)
[![Usability test findings on the Event Logs page before it's redesign](/212-RMO-EventLogsPage-NewDesign-01.avif)](../../../public/212-RMO-EventLogsPage-NewDesign-01.avif)
For more images on the design, visit

# Prototyping and Testing
- Low-fidelity wireframes and high-fidelity designs were created as the project progressed.
- Usability testing teased out any remaining, glaring issues in our implemented solution.
- Comprehensive accessibility testing included testing tab stop functionality, automated checks, and analysis of HTML heading structure using Accessibility Insights for the Web and ANDI.

[![Usability test findings on the Event Logs page before it's redesign](/212-RMO-PostTest-EventLogsPage.avif)](/212-RMO-PostTest-EventLogsPage.avif)
[![Usability test findings on the Event Logs page before it's redesign](/212-RMO-EventLogsPage-AccessibilityTesting.avif)](/212-RMO-EventLogsPage-AccessibilityTesting.avif)


# Collaboration with Development
- Regular communication with developers throughout the implementation phase.
- Relayed updates and design modifications based on user feedback.
- Provided frontend guidance to developers to ensure alignment with the evolving design.

# Conclusion
- **Impact**: Enhanced user task completion with ease rate from 10% to 80%.
- **Key takeaways**: Importance of scope, innovative pagination solutions, thoughtful progressive disclosure.
- This project would not be possible if not for my usability testing participants, management, business analysts, developers, and other team members who contributed to the success of the project. Thank you!