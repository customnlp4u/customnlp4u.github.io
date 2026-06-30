---
layout: page
permalink: /speakers/
title: Speakers
nav: false
nav_order: 3
---

## Invited Speakers

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/jneville-headshot.jpg" alt="Jennifer Neville">
            <p><a href="https://jenneville.github.io/">Jennifer Neville</a>
            <br>Microsoft Research / Purdue University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/Ramya_Korlakai_Vinayak.jpg" alt="Ramya Korlakai Vinayak">
            <p><a href="https://ramyakv.github.io/">Ramya Korlakai Vinayak</a>
            <br>UW-Madison</p>
        </div>
    </div>
</html>

<br>

#### Understanding Behavior for Personalized AI

__Speaker:__ [Jennifer Neville](https://jenneville.github.io/), Microsoft Research / Purdue University

__Abstract:__ Modern AI systems achieve impressive performance on benchmarks composed of isolated, fully specified tasks. Personal AI assistants, however, operate under very different conditions. Users communicate goals through evolving conversations, leave important details implicit, refine requests over time, and combine tasks into long-running workflows. These realistic interactions require AI systems to continually infer user intent, preserve information across context, and adapt their behavior as interactions unfold.
In this talk, I will argue that reliable personalization requires reliable behavior. Drawing on recent work spanning complex reasoning, multi-turn conversations, and long-horizon workflows, I will present empirical and theoretical results that reveal recurring failure modes as interaction complexity increases. Together, these findings provide a foundation for understanding why AI systems struggle to adapt reliably to users, and suggest new evaluation paradigms that better reflect the challenges of personalized AI.

__Bio:__ Jennifer Neville is a Partner Research Manager at Microsoft Research Redmond, where she leads the AI Interaction and Learning research group, and the Samuel Conte Chair Professor of Computer Science and Statistics at Purdue University. Her research focuses on understanding how machine learning and AI systems behave in realistic settings, from relational and networked data to modern AI assistants and agents. She is particularly interested in how mismatches between modeling assumptions and deployment environments shape system behavior. Jennifer has authored more than 150 publications with over 12,000 citations across machine learning and artificial intelligence. Her honors include an ICLR 2026 Best Paper Award, NSF CAREER Award, and IEEE's "10 to Watch in AI." She served as Program Chair of AAAI 2023 and has held leadership roles at NeurIPS, ICML, and IJCAI.

<br>

#### Sample-Efficient Personalized Preference Learning for Pluralistic Alignment

__Speaker:__ [Ramya Korlakai Vinayak](https://ramyakv.github.io/), UW-Madison

__Abstract:__ Large pre-trained generative models such as large language models trained on internet-scale data are often not ready for deployment out-of-the-box. They are heavily fine-tuned and aligned using large quantities of human preference data, usually elicited using pairwise comparisons. While aligning an AI/ML model to human preferences or values, it is important to ask whose preferences and values we are aligning it with? The prominent approaches to preference alignment are severely limited due to the inherent assumption of uniformity in the preference models. We overcome this limitation by building mathematical foundations for learning heterogeneous human preferences. In this talk, I will present PAL, a personalizable reward modeling framework for pluralistic alignment. PAL has a modular design that leverages commonalities across users while catering to individual personalization, enabling efficient few-shot generalization to new users. PAL is versatile enough to be applied to various domains and matches or outperforms state-of-the-art methods on both text-to-text and text-to-image generation tasks with 100x fewer parameters in practice. I will also present mathematical foundations that provide insight into the number of samples needed per user for generalization and the fundamental limitations when there are limited pairwise comparisons, which inform how the data should be collected in practise for the personalization of preferences.

__Bio:__ Ramya Korlakai Vinayak is the Dugald C. Jackson assistant professor in the Dept. of ECE and affiliated faculty in the Dept. of Computer Science and the Dept. of Statistics at the UW-Madison. Her research interests span the areas of machine learning, statistical inference, and human-AI collaboration, with a focus on preference learning and alignment under heterogeneity, reliable and efficient dataset creation, and human-in-the-loop systems. Her works address theoretical and practical challenges that arise when learning from heterogeneous societal-scale data. Prior to joining UW-Madison, she was a postdoctoral researcher in the Paul G. Allen School of Computer Science and Engineering at the University of Washington. She received her Ph.D. in Electrical Engineering from Caltech. She obtained her Masters from Caltech and Bachelors from IIT Madras. She is a recipient of the Schlumberger Foundation Faculty of the Future fellowship from 2013-15, and an invited participant at the Rising Stars in EECS workshop in 2019. She is the recipient of NSF CAREER Award in 2023.

<!--
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/diyi.jpg" alt="Diyi Yang">
            <p><a href="https://cs.stanford.edu/~diyiy/">Diyi Yang</a>
            <br>Stanford University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/hannah.jpeg" alt="Hannah Rose Kirk">
            <p><a href="https://www.hannahrosekirk.com/">Hannah Rose Kirk</a>
            <br>University of Oxford</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/jared.jpg" alt="Jared Roesch">
            <p><a href="https://jroesch.github.io/">Jared Roesche</a>
            <br>Nvidia, ex-Octo AI, University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/maartje.jpg" alt="Maartje Ter Hoeve">
            <p><a href="https://maartjeth.github.io">Maartje ter Hoeve</a>
            <br>Apple ML Research</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/x.jpg" alt="Mitchell">
            <p><a href="#">Mitchell</a>
            <br>Columbia University</p>
        </div>
    </div>
</html>
-->

<!-- <html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/hannah.jpg" alt="Hannah Rose Kirk">
            <p><a href="https://www.hannahrosekirk.com/">Hannah Rose Kirk</a>
            <br>University of Oxford</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/jared.jpg" alt="Jared Roesch">
            <p><a href="https://jroesch.github.io/">Jared Roesche</a>
            <br>Octo AI, University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/diyi.jpg" alt="Diyi Yang">
            <p><a href="https://cs.stanford.edu/~diyiy/">Diyi Yang</a>
            <br>Stanford University</p>
        </div>
        <!-- <div class="team-member">
            <img src="/assets/img/speakers/x.jpg" alt="Mitchell">
            <p><a href="#">Mitchell</a>
            <br>Columbia University</p>
        </div>
    </div>
</html> -->


<style>
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

<br><br>


<!-- 
#### Empowering Instruction Following Research with Language Models as Simulators

[[Slides]](/assets/pdf/Tatsunori_Hashimoto_Talk.pdf)

__Speaker:__ Tatsunori Hashimoto, Stanford University

__Time:__ 9:00am-9:30am


__Abstract:__ Instruction-following language models have driven remarkable progress in a range of NLP tasks and have been rapidly adopted across the world. However, academic research into these models has lagged behind due to the lack of open, reproducible, and low-cost environments with which to develop and test instruction-following models. In this talk, I will discuss how new, emerging approaches that study an LLM's ability to emulate human annotators and API endpoints hold promise in improving and critiquing LLMs. To improve instruction-following methods, recent work from our group such as AlpacaFarm shows how an LLM-based simulator can help test scientific hypotheses (e.g. is reinforcement learning helpful?) develop better instruction-following methods, and red-team LLMs in a more open and reproducible way. At the same time, there are major limits to LLMs’ ability to simulate annotators — such as in the opinions they reflect or the consistency of their responses — and we will discuss how these gaps raise important open problems in the trustworthiness of existing LLMs.

__Bio:__ Tatsunori Hashimoto is an Assistant Professor in the Computer Science Department at Stanford University. He is a member of the statistical machine learning and natural language processing groups at Stanford, and his research uses tools from statistics to make machine learning systems more robust and trustworthy — especially in complex systems such as large language models. He is a Kavli fellow, a Sony and Amazon research award winner, and his work has been recognized with best paper awards at ICML and CHI. Before becoming an Assistant Professor, he was a postdoctoral researcher at Stanford with Percy Liang and John Duchi and received his Ph.D. from MIT under the supervision of Tommi Jaakkola and David Gifford.

<br>
#### Manual Curation vs. AI Distillation: Lessons Learned for Instruction Following and Feedback Fine-tuning 

[[Slides]](https://www.nazneenrajani.com/neurips_instruction_tuning.pdf)

__Speaker:__ Nazneen Rajani 

__Time:__ 9:30am-10:00am

__Abstract:__ There has been a slew of work in training helpful conversational agents using Large language models (LLMs). These models draw upon diverse datasets, including open-source repositories, private data, and even synthetic data generated from LLMs. However, curating datasets for SFT and RLHF involves critical decisions, such as defining task distributions, data volume, prompt length, and more. While prior research underscores the importance of data quality, the nuanced impact of these various dataset factors on model performance remains unclear. I’ll present and compare our approaches for data curation using human labor and AI distillation in the context of training helpful chatbots. I will delve into the results of experiments that illuminate the nuanced effects of different dataset attributes on the training process of helpfulness in chatbots.

__Bio:__ Most recently, Nazneen was a Research lead at Hugging Face and worked on alignment and AI safety, and evaluation. Recently, she and her team released the Zephyr model, which is already part of You.com's product offerings. Nazneen is selected by the UN's secretary general to serve on the AI Advisory Body along with other global experts in AI https://www.un.org//ai-advisory-body. More details about my work can be found at https://www.nazneenrajani.com/


<br>
#### Towards Instruction Following Robots

__Speaker:__ Fei Xia

__Time:__ 10:15am-10:45am

__Abstract:__ This talk focuses on the integration of instruction-following language models in the field of robotics, leveraging two novel concepts: Affordance and Language to Reward (L2R). Affordance, as proposed in existing literature, provides a framework for robots to understand and interact with their environment in a meaningful way. It is defined as the potential actions that an environment enables for an agent, thereby granting robots the ability to execute tasks in various contexts. This concept allows robots to generate plans that are grounded in their environments. On the other hand, Language to Reward (L2R), proposes a new way to use language models in robotics zero-shot.. L2R utilizes reward functions as a flexible interface, bridging the gap between abstract language instructions and specific, actionable tasks for robots. Through this method, language models can define reward parameters, which are then optimized to direct robot actions effectively. The use of a real-time optimizer, such as MuJoCo MPC, enhances this process by allowing for an interactive and dynamic experience. Users can instantly see the outcomes of their instructions, providing immediate feedback that can be used to modify and improve the robot's behavior.

__Bio:__ Fei Xia is a senior research scientist at Google DeepMind, focusing on the field of robotics. His work involves building intelligent agents capable of interacting with complex, unstructured real-world environments, with applications in home robotics. Recently his work centers around foundation models for robotics: This involves using large language models (LLMs) to learn general-purpose skills that can be applied to a variety of robotic tasks.


<br>
#### Challenges and Open Opportunities in Instruction Tuning: The Case Study of AYA

__Speaker:__ Sara Hooker

__Time:__ 2:00pm-2:30pm

__Abstract:__ In this talk, to frame many of the open challenges and opportunities with instruction tuning, I'll share some of the lessons learned and open questions spurred by AYA. AYA is a year long open science endeavor aimed at building a multilingual language model via instruction tuning that harnesses the collective wisdom and contributions of independent researchers across the world. It aims to improve coverage of instruction finetuned datasets for 101 languages around the world. The project was initiated by Cohere For AI as a multi-institutional collaboration with researchers, engineers, linguists, social scientists, and lifelong learners from over 100 countries around the world. I'll use this setting as a springboard to discuss a wider set of research directions on instruction finetuning optimization approaches.

__Bio:__ Sara Hooker leads Cohere For AI, a non-profit research lab that seeks to solve complex machine learning problems. Cohere For AI supports fundamental research that explores the unknown, and is focused on creating more points of entry into machine learning research. With a long track-record of impactful research at Google Brain, Sara brings a wealth of knowledge from across machine learning. Her work has focused on model efficiency training techniques and optimizing for models that fulfill multiple desired criteria -- interpretable, efficient, fair and robust. Before Cohere For AI, she was the founder of Delta Analytics, a non-profit that brings together researchers, data scientists, and software engineers to volunteer their skills for non-profits around the world.

<br>
#### Beyond Instruction Following 

[[Slides]](https://docs.google.com/presentation/d/1geLScLm6rGj-tWU5EeQh-oGvkKAUgGSBGUpRSETKOuI/edit#slide=id.p)

__Speaker:__ Alex Tamkin

__Time:__ 2:30pm-3:00pm

__Abstract:__ This talk will discuss some open research challenges and opportunities surrounding the role of instructions in instruction following models. I'll also discuss our recent work on Eliciting Human Preferences with Language Models (Li and Tamkin et al 2023) which aims at addressing some of these challenges.

__Bio:__ Alex Tamkin is a research scientist at Anthropic. Previously, he was a PhD student in Computer Science at Stanford, where he was a part of the Stanford AI Lab and Stanford NLP Group.
 -->
