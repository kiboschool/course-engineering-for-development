# Tools and Techniques for Problem Analysis

<aside>

🗣 “Technique is the test of sincerity. If a thing isn't worth getting the technique to say, it is of inferior value.”
-**Ezra Pound**

</aside>

Problem analysis is a systematic approach to understanding and addressing complex issues. It involves using a variety of tools and techniques to identify the root causes of a problem and develop solutions that address those causes.

There are many commonly used tools and techniques for problem analysis. In this lesson, we will focus on four of these techniques.

- Root Cause Analysis
- Problem Tree Analysis
- Fishbone Diagram/Analysis
- Pareto Analysis

---

## Root Cause Analysis (RCA)

This is a systematic approach to identifying the underlying causes of a problem. It can be used to identify the root causes of problems in a variety of settings, such as business, healthcare, and education.

> 📖 Read this Tableaux [article](https://www.tableau.com/learn/articles/root-cause-analysis#:~:text=Root%20cause%20analysis%20(RCA)%20is,symptoms%20and%20putting%20out%20fires.) to learn more about root cause analysis.

> 📺 Watch this video for an in-depth explanation of the definition, examples, and methods of root cause analysis.

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.youtube.com/embed/f0TCGAHpgCs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

From the article, we learn that there are a few core principles that guide effective root cause analysis. They include;

- Focus on correcting and remedying root causes rather than just symptoms.
- Don’t ignore the importance of treating symptoms for short-term relief.
- Realize there can be, and often are, multiple root causes.
- Focus on HOW and WHY something happened, not WHO was responsible.
- Be methodical and find concrete cause-effect evidence to back up root cause claims.
- Provide enough information to inform a corrective course of action.
- Consider how a root cause can be prevented (or replicated) in the future.

### How  to  conduct root cause analysis

Read and learn how to conduct root cause analysis from Tobi’s experience

> **Meet Tobi**
>
> Tobi is a skilled system administrator at the tech startup InnovateTech and was facing a perplexing issue. The company's servers have crashed, causing a massive disruption in their services.
>
> **Crisis Unfolds:** One gloomy Monday morning, Tobi received a barrage of emails and frantic calls from colleagues and clients. The company's flagship product, an e-commerce platform, had gone offline. The support team was overwhelmed with customer complaints, and the CEO was breathing fire. Tobi knew they needed to act swiftly.
>
> **Immediate Response: T**obi's initial response was to reboot the servers, which temporarily restored service. However, he knew this was just a Band-Aid solution. The problem was bound to resurface unless they addressed the root cause.
>
> **Assembling the Team:** Tobi decided to gather a team for a root cause analysis. He included Jane from the software development team, Mike from networking, and Sarah, a customer support representative. He knew diverse perspectives were key to uncovering the underlying issue.
>
> **Mapping the Problem:** Together, the team outlined the problem. They identified the symptoms: server crashes, inconsistent response times, and a flood of error messages. They knew these were only the surface of the issue.
>
> **Asking "Why?"**
>
> Following the principles of root cause analysis, they began asking the "5 Whys." Each "Why" led them deeper into the problem:
>
> Why 1: Why did the server crash? Because it couldn't handle the sudden spike in traffic.
>
> Why 2: Why couldn't it handle the traffic? Because there were too many connections open to the database.
>
> Why 3: Why were there so many open connections? Because the database queries weren't optimized.
>
> Why 4: Why weren't the queries optimized? Because recent software updates changed the database structure.
>
> Why 5: Why didn't the team catch this in testing? Because there was no automated regression testing for database performance.
>
> **Identifying the Root Cause:** At the fifth "Why," they realized the core issue was the absence of automated regression testing for database performance. The recent updates had unknowingly strained the database, leading to server crashes during peak usage.
>
> **Solutions and Preventative Measures:** With the root cause identified, they brainstormed solutions. They decided to implement automated database performance testing as a priority. They also established a post-update checklist to catch potential issues early.
>
> **Post-Analysis:** Once the changes were implemented, Tobi's team monitored the system closely. Thanks to their rigorous root cause analysis, future server crashes were averted. The team's efforts didn't just resolve the immediate crisis but also improved the company's overall system stability.
>
> **Lessons Learned:** Tobi and his team knew that conducting root cause analyses was more than just problem-solving; it was about learning from mistakes and continuously improving processes. They implemented regular reviews and training sessions to ensure they remained vigilant.

> 🪞 **Reflection:** Reflecting on Tobi's experience, can you think of a time when you encountered a problem that seemed simple on the surface but had a complex underlying cause? How did you approach solving it, and what did you learn from that experience?

<div style="border:1px solid rgba(0,0,0,0.1);border-radius:2px;box-sizing:border-box;overflow:hidden;position:relative;width:100%;background:#F4F4F4"><iframe src="https://padlet.com/embed/cftcduyi2qmvii0" frameborder="0" allow="camera;microphone;geolocation" style="width:100%;height:708px;display:block;padding:0;margin:0"></iframe></div>

---

## The Problem Tree Analysis

Problem Tree Analysis is a powerful technique used in problem analysis and project planning. It is particularly valuable for understanding the root causes and consequences of complex issues. Imagine it as a visual representation of a problem's structure, with the trunk representing the core problem and the branches symbolizing its causes and effects.

Let's delve deeper into this technique.

> 📖 First, read the ODI [publication](https://odi.org/en/publications/planning-tools-problem-tree-analysis/) on problem tree analysis for more insight into the technique.

From the article, we learned about the advantages of problem tree analysis. They include;

1. **Enhanced Problem Decomposition:** Problem Tree Analysis breaks complex issues into manageable and well-defined components. This facilitates clearer prioritization of factors, aiding in the precise definition of objectives.
2. **In-Depth Understanding:** This method promotes a deeper comprehension of the problem, including its intricate and sometimes conflicting causes. Such understanding is often the initial step toward discovering mutually beneficial solutions.
3. **Identification of Stakeholders:** Problem Tree Analysis identifies the constituent issues and stakeholders involved. It can elucidate the political actors and processes at each stage, offering valuable insights for effective problem resolution.
4. **Resource Assessment:** It assists in evaluating whether additional information, evidence, or resources are required to construct a robust case or develop a convincing solution.
5. **Focus on Present Issues:** The analysis primarily addresses current issues rather than apparent, future, or past concerns, ensuring that immediate challenges are dealt with effectively.
6. **Fostering Shared Understanding:** The analytical process often cultivates a shared sense of comprehension, purpose, and collaborative action among stakeholders. This collective understanding can be a catalyst for effective problem-solving and decision-making.

Problem Tree Analysis is indeed a versatile tool that goes beyond identifying problems; it helps lay the groundwork for systematic problem resolution and effective decision-making.

> 📺 Watch this explainer video for a step-by-step guide on how to conduct a problem tree analysis.

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.youtube.com/embed/q6qYZiW5BWU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

From the video, we learned three key steps of problem tree analysis. They include;

1. **Identifying the problem.** This can be done through community needs analysis or classroom discussions. Once a problem is chosen, it becomes the trunk of the problem tree diagram.
2. **Researching the problem.** Gather insights from various community members to comprehend the underlying issues and perspectives related to the problem. Each cause leading to the problem can be envisioned as the roots of the tree, and it's essential to identify them thoroughly. Additionally, explore the effects of the problem, which can be represented as the branches of the tree.
3. **Brainstorm solutions.** Once you have a problem and a clear understanding of its causes and effects, it's time to brainstorm possible solutions. The information gathered in the problem tree can guide this brainstorming process. Different causes may suggest various solutions.

A problem tree analysis can be applied to both local and global problems. By following these steps, you, too can use problem tree analysis to make a positive impact on your community.

> ❓ Reflection Activity: You are a computer science college student. You have noticed that many of your classmates are struggling to pass their classes, and you want to do something to help, so you decide to conduct a problem tree analysis.
>
> **Reflection question**: What are some of the possible causes (roots) of computer science students struggling to pass their classes?
Share your thoughts in the padlet below.

<div style="border:1px solid rgba(0,0,0,0.1);border-radius:2px;box-sizing:border-box;overflow:hidden;position:relative;width:100%;background:#F4F4F4"><iframe src="https://padlet.com/embed/qgxos6eim3r61utm" frameborder="0" allow="camera;microphone;geolocation" style="width:100%;height:708px;display:block;padding:0;margin:0"></iframe></div>

---

## Fishbone Diagram/Analysis

This analysis, also known as the Ishikawa Diagram or Cause-and-Effect Diagram, is a problem analysis technique used to identify the root causes of a particular issue or problem. It was developed by Dr. Kaoru Ishikawa, a Japanese quality control expert, and is widely employed in various industries, including manufacturing, healthcare, and project management.

> 📺 Watch this video for an explanation of Fishbone Analysis and its key components.

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.youtube.com/embed/JbRx5pw-efg?si=nXJ5IrU20VFMFQCh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

In the video, we learn that the anatomy of the fish in the fishbone diagram has three parts:

- **Head of the fish:** This part represents the problem statement or the issue that you are trying to solve.
- **Backbone:** The backbone of the diagram connects to the bones, each of which represents a range of potential causes of the problem.
- **Bones:** These bones group related causes into categories.

> ❓ Can you recall the four steps involved in a fishbone analysis?

<details> 
   <summary> Answer </summary>

The four steps are as follows:
   1. **State the Problem:** Begin by framing the problem as a question. For example, "Why did our website crash?" Update the Fishbone Diagram to reflect this question.
    2. **Define Categories:** Establish the categories that will guide your brainstorming session. These categories can evolve as your thinking progresses but serve as a starting point. For instance, "System," "Process," and "Human" categories can be relevant for a website crash analysis.
    3. **Brainstorm Causes:** Delve into each category one by one, generating a list of potential causes. Employ the "Five Whys" technique to dig deeper and uncover the root causes. This technique involves asking "why" five times to unveil the true source of the problem.
    4. **Analyze Results:** Continuously update your Fishbone Diagram as you brainstorm. Your final diagram will likely contain a plethora of causes, providing a comprehensive overview of the issue.

</details>

---

## Pareto Analysis

You most likely will have heard of the 80/20 rule or the Pareto principle. It is a familiar saying that asserts that 80% of outcomes (or effects) result from 20% of all causes (or inputs) for any given event.

In the problem analysis context, Pareto analysis is a technique for identifying the most important causes of a problem. It is based on the Pareto principle.

In Pareto analysis, a list of causes is created and then ranked in order of importance. The causes are then divided into two groups: the vital few and the trivial many. The vital few are the causes that have the biggest impact on the problem, while the trivial many are the causes that have a smaller impact.

Pareto analysis can be used to identify the most important causes of a problem so that they can be addressed first. It can also be used to prioritize tasks and to allocate resources.

> 📺 Watch this explainer video on Pareto analysis for more insight.

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.youtube.com/embed/eYIzaLoYd_4?si=3hR2TJdRqhwUFCx1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

The speaker in the video explains that the Pareto analysis is not a magic wand that can eliminate all non-critical aspects of a situation. However, it is a pragmatic approach to shifting our focus to the areas with the greatest potential impact. For businesses, this means identifying and prioritizing underperforming aspects to achieve maximum results. Successful businesses routinely employ the Pareto analysis to ensure that every facet of their operations contributes to overall success.

Pareto analysis is a valuable tool that transcends industries and situations. It offers a structured and data-driven approach to problem analysis. By embracing the power of Pareto, individuals and organizations alike can navigate complex challenges with clarity and efficiency.

> **Meet Alex**
>
> Alex is a computer science student interning at a software development company. The company's flagship software application has been plagued by a multitude of bugs lately, affecting both user experience and the company's reputation. Alex, eager to contribute, sees an opportunity to apply Pareto Analysis, a problem analysis technique he learned during his second year at the university.
>
> Alex begins by working closely with the development team. Together, they gather detailed data on every reported bug over the course of a month. Each bug is categorized based on its severity and the number of users affected, with Alex meticulously documenting the findings.
>
> Once the data is collected and analyzed, the results reveal a significant pattern:
> **Crashes and System Freezes** - These issues are the most severe, affecting a whopping 70% of users.
> **Security Vulnerabilities** - Although less frequent, these vulnerabilities impact 20% of users.
> **Minor Interface Glitches** - While numerous, these glitches affect only 10% of users.
>
> Alex gathers the development team and leads a discussion centered around Pareto Analysis. He asks a thought-provoking question: "Now that we've used Pareto Analysis to identify crashes and system freezes as the most critical issues, how should we prioritize our efforts to fix them? Can you think of strategies that would help us ensure the software becomes more stable and reliable, ultimately enhancing user satisfaction?"
> 
> The team begins to brainstorm, focusing on Pareto Analysis as their guiding principle for tackling these critical bugs.

> ❓ **Discussion Activity**: In the story, Alex used Pareto Analysis to prioritize and tackle software bugs. Now, imagine you're the lead developer of this project. How would you not only fix the crashes and system freezes but also prevent them from happening in the future?
>
> Share (on the Padlet) your strategies and discuss how Pareto Analysis (or another problem analysis technique of your choice) can guide you in achieving a more robust software solution while balancing resource constraints.

<div style="border:1px solid rgba(0,0,0,0.1);border-radius:2px;box-sizing:border-box;overflow:hidden;position:relative;width:100%;background:#F4F4F4"><iframe src="https://padlet.com/embed/2x8bikvk3a35owoc" frameborder="0" allow="camera;microphone;geolocation" style="width:100%;height:708px;display:block;padding:0;margin:0"></iframe></div>

---

### Congratulations on completing the first part of our journey into problem analysis!

In this lesson, you've delved into the fundamental principles, tools, and techniques that underpin effective problem analysis. You've learned the importance of problem analysis, explored various techniques such as Fishbone analysis and Pareto analysis, and delved into the concept of interconnectedness.

Now, as we transition into Lesson 7, we will build upon this foundation. Problem Analysis II will take us deeper into the practical application of these principles. In this upcoming lesson, we'll navigate through real-world case studies related to Sustainable Development Goal 6 (SDG 6) to gain a hands-on understanding of how to analyze complex issues, identify root causes, and propose effective solutions.

SDG 6 focuses on ensuring the availability and sustainable management of water and sanitation for all. By applying the problem analysis techniques you've acquired in this lesson, we'll dissect the challenges surrounding clean water and sanitation, exploring the intricacies of interconnected problems and potential solutions.

So, get ready to put your problem analysis skills to the test in Lesson 7. As we tackle the global issues presented by SDG 6, you'll have the opportunity to apply what you've learned, engage in insightful discussions, and further enhance your problem-solving abilities.

Remember, effective problem analysis is not only a valuable skill in the realm of computer science but also an essential tool for addressing complex challenges in the broader context of sustainable development.
