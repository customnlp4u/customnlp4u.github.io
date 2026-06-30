---
layout: page
permalink: /schedule/
title: Schedule
nav: true
nav_order: 2
---
# Schedule

| **Time** | **Session** |
|------|---------|
| 9:00-9:10 am | Opening remarks |
| 9:10-9:50 am | Keynote 1 – Jennifer Neville (Microsoft Research / Purdue University) |
| 9:50-10:30 am | Keynote 2 – Ramya Korlakai Vinayak (UW-Madison) |
| 10:30-11:00 am | Coffee break |
| 11:00-11:30 am | Lightning talks by accepted papers |
| 11:30 am-12:30 pm | Poster session |

# Invited Speakers

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/jneville-headshot.jpg" alt="Jennifer Neville">
            <p><a href="https://jenneville.github.io/">Jennifer Neville</a>
            <br>Microsoft Research / Purdue University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/Ramya_Korlakai_Vinayak.jpg" alt="Ramya Korlakai Vinayak" class="ramya-img">
            <p><a href="https://ramyakv.github.io/">Ramya Korlakai Vinayak</a>
            <br>UW-Madison</p>
        </div>
    </div>
</html>

<br>

#### Understanding Behavior for Personalized AI

__Speaker:__ Jennifer Neville, Microsoft Research / Purdue University

__Abstract:__ Modern AI systems achieve impressive performance on benchmarks composed of isolated, fully specified tasks. Personal AI assistants, however, operate under very different conditions. Users communicate goals through evolving conversations, leave important details implicit, refine requests over time, and combine tasks into long-running workflows. These realistic interactions require AI systems to continually infer user intent, preserve information across context, and adapt their behavior as interactions unfold.
In this talk, I will argue that reliable personalization requires reliable behavior. Drawing on recent work spanning complex reasoning, multi-turn conversations, and long-horizon workflows, I will present empirical and theoretical results that reveal recurring failure modes as interaction complexity increases. Together, these findings provide a foundation for understanding why AI systems struggle to adapt reliably to users, and suggest new evaluation paradigms that better reflect the challenges of personalized AI.

__Bio:__ Jennifer Neville is a Partner Research Manager at Microsoft Research Redmond, where she leads the AI Interaction and Learning research group, and the Samuel Conte Chair Professor of Computer Science and Statistics at Purdue University. Her research focuses on understanding how machine learning and AI systems behave in realistic settings, from relational and networked data to modern AI assistants and agents. She is particularly interested in how mismatches between modeling assumptions and deployment environments shape system behavior. Jennifer has authored more than 150 publications with over 12,000 citations across machine learning and artificial intelligence. Her honors include an ICLR 2026 Best Paper Award, NSF CAREER Award, and IEEE's "10 to Watch in AI." She served as Program Chair of AAAI 2023 and has held leadership roles at NeurIPS, ICML, and IJCAI.

<br>

#### Sample-Efficient Personalized Preference Learning for Pluralistic Alignment

__Speaker:__ Ramya Korlakai Vinayak, UW-Madison

__Abstract:__ Large pre-trained generative models such as large language models trained on internet-scale data are often not ready for deployment out-of-the-box. They are heavily fine-tuned and aligned using large quantities of human preference data, usually elicited using pairwise comparisons. While aligning an AI/ML model to human preferences or values, it is important to ask whose preferences and values we are aligning it with? The prominent approaches to preference alignment are severely limited due to the inherent assumption of uniformity in the preference models. We overcome this limitation by building mathematical foundations for learning heterogeneous human preferences. In this talk, I will present PAL, a personalizable reward modeling framework for pluralistic alignment. PAL has a modular design that leverages commonalities across users while catering to individual personalization, enabling efficient few-shot generalization to new users. PAL is versatile enough to be applied to various domains and matches or outperforms state-of-the-art methods on both text-to-text and text-to-image generation tasks with 100x fewer parameters in practice. I will also present mathematical foundations that provide insight into the number of samples needed per user for generalization and the fundamental limitations when there are limited pairwise comparisons, which inform how the data should be collected in practise for the personalization of preferences.

__Bio:__ Ramya Korlakai Vinayak is the Dugald C. Jackson assistant professor in the Dept. of ECE and affiliated faculty in the Dept. of Computer Science and the Dept. of Statistics at the UW-Madison. Her research interests span the areas of machine learning, statistical inference, and human-AI collaboration, with a focus on preference learning and alignment under heterogeneity, reliable and efficient dataset creation, and human-in-the-loop systems. Her works address theoretical and practical challenges that arise when learning from heterogeneous societal-scale data. Prior to joining UW-Madison, she was a postdoctoral researcher in the Paul G. Allen School of Computer Science and Engineering at the University of Washington. She received her Ph.D. in Electrical Engineering from Caltech. She obtained her Masters from Caltech and Bachelors from IIT Madras. She is a recipient of the Schlumberger Foundation Faculty of the Future fellowship from 2013-15, and an invited participant at the Rising Stars in EECS workshop in 2019. She is the recipient of NSF CAREER Award in 2023.
 



<style>
/* Add a bit more horizontal spacing between schedule table columns */
table th,
table td {
    padding-right: 24px;
}
table th:last-child,
table td:last-child {
    padding-right: 8px;
}

    /* Style for the team container */
.team-container {
    display: grid;
    grid-template-columns: repeat(5, 1fr); /* Display 3 members per row */
    gap: 5px;
    max-width: 1000px;
    padding: 20px;
}

@media (max-width: 768px) {
    .team-container {
        grid-template-columns: repeat(2, 1fr); /* Display 2 members per row on smaller screens */
    }
}

/* Style for each team member */
.team-member {
    text-align: center;
    background-color: #fff;
    padding: 0px;
    width: 150px; /* Set a fixed width for consistent circle appearance */
    height: 260px; /* Set a fixed height for consistent circle appearance */
    /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1); */
    overflow: hidden; /* Hide any image overflow */
}


.team-member h3 {
    font-size: 16px;
    color: #333;
}

.team-member img {
  object-fit: cover;
  border-radius:50%;
  width: 150px;
  height: 150px;
  padding: 10px;
}

.team-member img.ramya-img {
  object-position: center 20%;
}

.sponsor-container {
    display: flex;
    gap: 5px;
}

.sponsor {
    flex: 1;
    margin: 10px;
    text-align: center;
    box-sizing: border-box;
    height: 50px;
    width: 50px;
}

.sponsor img {  
    width: 100%; /* Make the image take up 100% of the figure's width */
    height: 100%;
    object-fit: contain; 
}

.caption {
    margin-top: 12px; /* Adjust the margin to control the gap between the figure and the caption */
}

.right-half {
    flex: 1; /* Each figure takes up 50% of the available width */
    height: 500px; /* Set a fixed height for all figures (adjust the value as needed) */
}
</style>
