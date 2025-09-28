# How ChatGPT can be used as an assistant to simplify the design process for beginners learning to use CAD in Blender.

## Abstract 
&nbsp;&nbsp;&nbsp;&nbsp;Learning CAD is difficult for beginners due to steep tool complexity and limited prior knowledge. This study investigates ChatGPT as a tutorial partner to support novices modeling a low-poly tree in Blender. It helps introduce users to this topic that are already interested but unsure how to start, making CAD easy to learn through an accessible way, and simple to understand. Ten beginners were recruited to have a structured tutorial that encouraged explanation, error diagnosis, and small edits, rather than full designs. To test efficiency a survey was used that measured task completion, time on tasks, interaction, and pre and post efficacy. Ethics of AI use to model objects was also taken into account, and responses were collected from the same survey. The project shows that AI tutored learners completed the model in under 30 minutes, reported increased confidence, and have better understanding. This tutoring workflow is easy to replicate and evidence supports this approach.

## Introduction
&nbsp;&nbsp;&nbsp;&nbsp;Computer-aided design (CAD), is an important tool for many fields such as engineering, architecture, and product design. However, it can be challenging to learn how to use CAD software, since it requires a lot of training, technical knowledge, and a lot of time for practice to be familiarized and comfortable with the tools (Gutiérrez de Ravé, 2025). Since beginners may have limited time or little to no experience, this can be discouraging. Artificial Intelligence tools may offer solutions. According to Choi (2025), new AI tools can be used in many ways and be leveraged to assist with CAD design workflow, but that these tools are still complicated and unproven. AI has shown potential to enhance and simplify various aspects of design. For example, deep generative models can translate high-level design ideas to usable CAD models, requiring little user input, which can give users a starting point for their projects (Wu 2021). This can help guide users without needing to master tools. In the field of structural design, generative AI has already helped automate early-stage tasks, suggesting similar tools could simplify CAD processes (Liao 2025). 

&nbsp;&nbsp;&nbsp;&nbsp;There are also studies that show how AI changed the way designers think and work during the first phases of a project. AI can help as a creative co-designer, which can offer new suggestions and help users explore different ideas (Saadi 2023). This collaboration can help beginners think about ways to change their project while making progress to their final design. Other studies have shown that AI in CAD is evolving to shift the role of users from passive operators to active collaborators, creating an engaging experience (Zou 2024). These studies demonstrate that AI is still complex, but using it as a tutor, there is room to leverage what AI is good at, and it can play a role in helping beginners with CAD. However, these tools still need to be explored to see how they can be designed and tested for learners that are new. Through this project, I seek to explore how ChatGPT can be used as an assistant to simplify the design process for beginners learning to use Blender to make CAD. To test the effectiveness, user feedback through surveys was collected. The final goal is to show how AI can guide people and be a tool and helpful partner in CAD design. This project seeks to explore how ChatGPT can guide users as an assistant to be a helpful partner and simplify the design process of new users learning to use Blender to create CAD, tested by survey data.

## Methodology:
&nbsp;&nbsp;&nbsp;&nbsp;**Choosing a system:** Several methods were considered to find the most efficient way to help new users with CAD. This includes softwares such as Fusion, OnShape, AutoCAD, SketchUP, and Solidworks, and AI’s like Gemini and Copilot. The method chosen for this project was to use the capabilities of ChatGPT, an AI, with Blender, a CAD and modeling software, since both are very accessible, and it's a flexible approach for beginners to engage with CAD design. Unlike AI-integrated CAD platforms which have subscription fees or need special knowledge to understand, using these combines an open-source 3D modeling tool, Blender, with a widely available AI chatbot, ChatGPT. By using ChatGPT as a tutor, users can receive guidance, make code, ask AI about errors, and gain more of an understanding for scripting logic with Blender's python API. The upside is that all of this requires no prior programming experience.

&nbsp;&nbsp;&nbsp;&nbsp;This method supports iterative learning, a learning process that involves repeated cycles of trying, evaluating, and refining, which can be very beneficial for beginners. Instead of just relying on fixed tutorials and templates, users can constantly ask questions, receive answers specific to what they're working on, and request specific scripts based on design goals. It also helps with experimentation, allowing them to develop creative confidence. It stimulates a teaching environment, and can help make CAD more approachable, interactive, and efficient.
</p>

&nbsp;&nbsp;&nbsp;&nbsp;**Developing a process** The process that was developed shows how users can interact with ChatGPT as a tutor to help them work with CAD in Blender. Instead of just generating models, ChatGPT is used as a narrative process tutor that supports users to understand the concepts of how they are making the models. The purpose of ChatGPT is to explain, guide, and answer questions during the modeling process. This helps users build skills and confidence when working with Blender's python API. This approach mainly focuses on the idea of learning something by actually making it.

&nbsp;&nbsp;&nbsp;&nbsp;To guide the user experience, several prompt strategies were used to help  users learn rather than result-focused generation. The goal was to make ChatGPT act like a teacher, explaining code, offering feedback, and guiding the user through the problems that they encounter. A survey was made to provide evidence of the method working, and was sent out to 10 people.

**Prompting examples:**

&nbsp;&nbsp;&nbsp;&nbsp;Some examples of prompts that worked include: "Can you explain what this blender python code does, line by line?", "How can I modify this code to make the object wider?", "What is the difference between scaling and resizing in Blender?", "Why am I getting this error in blender?", "Can you help me make this object step by step?".


&nbsp;&nbsp;&nbsp;&nbsp;Some prompts that didn't work well were: "What script do I use to make a table in Blender like IKEA's LACK?", "What's wrong with this script?" (user pastes 50+ unformatted lines of code), "How do I use modifiers in Blender?", "How can I make a complex mechanical object with gears and joins user Blender Python?", "Can you give me a script that uses geometry nodes?" These prompts failed since they lacked enough technical detail or context, involved visual issues, and combined multiple concepts. 

&nbsp;&nbsp;&nbsp;&nbsp;While ChatGPT was effective in teaching some concepts in a step by step process, certain prompts showed its limitations. This was especially shown when users asked overly broad or highly specific questions, such as not having enough technical detail or context, and combining too many concepts. These cases show how it's important to learn how to ask effective, focused prompts when using ChatGPT as a tutor.

&nbsp;&nbsp;&nbsp;&nbsp;This method was successful since instead of copying full scripts, users were able to ask questions while making their design at their own pace, get explanations, understand what they were doing, and tweak their code based on feedback. This created an interactive, personalized, and educational process.

&nbsp;&nbsp;&nbsp;&nbsp;When choosing which method to use, prompts were tested to determine which produced the best responses and were most useful in Blender. The responses of the chosen method are included in the tutorial, located on the linked website.

**https://1r-obo.github.io/AI-CAD-Project/**

## Results: What happened and whether it was a success
&nbsp;&nbsp;&nbsp;&nbsp;A survey was distributed and collected responses from 10 participants. The data showed consistent improvement, with overall positive feedback regarding the tutorial as well as the experience of working with AI. The target goal for time was that the participants were able to complete making the object in 30 minutes or less, and every participant met the goal, with time ranging from 7 to 30 minutes. Most participants began with a self-assessed experience level of 1 from a scale of 1 through 5, and ended with a confidence level ranging 3 to 5 on a scale of 1 through 5. Responses indicated that the tutorial was helpful and provided a necessary starting point; without it, learning CAD would feel difficult and discouraging.

## Analysis/Discussion: 
&nbsp;&nbsp;&nbsp;&nbsp;From the survey, AI as a tutor was shown to be very effective in the participants modeling. Regarding ethics, most participants had positive opinions, and were fine with AI acting as a tutor, since it was like another tool. Some of the responses collected say: "Using chatgpt is fine as long as you are using it as a learning look. As for ethics, it's just another way to learn skills so I don't think it qualifies as cheating", "I feel like it helps and does not feel like cheating since you’re leveraging additional information to learn. Ethically, if it’s allowed then it should be good to use, however, if we are told not to use it, then it would be unethical.", "I think that Chatgpt can be used in either good or bad ways and these ways could both contribute to our knowledge and help us in things. I think that its not really cheating if your just asking it for help on explaining how to do something."


## Conclusion: N/A (for now)


## References:
**Choi, Jiin, et al.** “Toward AI-Driven Multimodal Interfaces for Industrial CAD Modeling.” *arXiv:2503.16824*, arXiv, 21 Mar. 2025. arXiv.org, [https://doi.org/10.48550/arXiv.2503.16824](https://doi.org/10.48550/arXiv.2503.16824).

**Daareyni, Amirmohammad, et al.** “Generative AI Meets CAD: Enhancing Engineering Design to Manufacturing Processes with Large Language Models.” *The International Journal of Advanced Manufacturing Technology*, June 2025. Springer Link, [https://doi.org/10.1007/s00170-025-15830-2](https://doi.org/10.1007/s00170-025-15830-2).

**“Generative AI Design for Building Structures.”** *Automation in Construction*, vol. 157, Jan. 2024, p. 105187. ScienceDirect, [https://doi.org/10.1016/j.autcon.2023.105187](https://doi.org/10.1016/j.autcon.2023.105187).

**Gutiérrez de Ravé, Simón, et al.** “Enhancing Efficiency and Creativity in Mechanical Drafting: A Comparative Study of General-Purpose CAD Versus Specialized Toolsets.” *Applied System Innovation*, vol. 8, no. 3, June 2025, p. 74. MDPI, [https://doi.org/10.3390/asi8030074](https://doi.org/10.3390/asi8030074).

**Li, Kun-Ying, et al.** “Generative AI and CAD Automation for Diverse and Novel Mechanical Component Designs under Data Constraints.” *Discover Applied Sciences*, vol. 7, no. 4, Apr. 2025, pp. 1–21. Springer Link, [https://doi.org/10.1007/s42452-025-06833-5](https://doi.org/10.1007/s42452-025-06833-5).

**“MLCAD: A Survey of Research in Machine Learning for CAD Keynote Paper.”** *ResearchGate*. [https://doi.org/10.1109/TCAD.2021.3124762](https://doi.org/10.1109/TCAD.2021.3124762). Accessed 15 July 2025.

**Regassa Hunde, Bonsa, and Abraham Debebe Woldeyohannes.** “Future Prospects of Computer-Aided Design (CAD) – A Review from the Perspective of Artificial Intelligence (AI), Extended Reality, and 3D Printing.” *Results in Engineering*, vol. 14, June 2022, p. 100478. ScienceDirect, [https://doi.org/10.1016/j.rineng.2022.100478](https://doi.org/10.1016/j.rineng.2022.100478).

**Regenwetter, Lyle, et al.** “Deep Generative Models in Engineering Design: A Review.” *arXiv:2110.10863*, arXiv, 16 Mar. 2022. arXiv.org, [https://doi.org/10.48550/arXiv.2110.10863](https://doi.org/10.48550/arXiv.2110.10863).

**Saadi, Jana I., and Maria C. Yang.** “Generative Design: Reframing the Role of the Designer in Early-Stage Design Process.” *Journal of Mechanical Design*, vol. 145, no. 4, Apr. 2023. ASME Digital Collection, [https://doi.org/10.1115/1.4056799](https://doi.org/10.1115/1.4056799).

**Wu, Rundi, et al.** “DeepCAD: A Deep Generative Network for Computer-Aided Design Models.” *arXiv:2105.09492*, arXiv, 16 Aug. 2021. arXiv.org, [https://doi.org/10.48550/arXiv.2105.09492](https://doi.org/10.48550/arXiv.2105.09492).

**Xu, Xiang, et al.** “SkexGen: Autoregressive Generation of CAD Construction Sequences with Disentangled Codebooks.” *arXiv:2207.04632*, arXiv, 11 July 2022. arXiv.org, [https://doi.org/10.48550/arXiv.2207.04632](https://doi.org/10.48550/arXiv.2207.04632).

**Zhang, Licheng, et al.** “Large Language Models for Computer-Aided Design: A Survey.” *arXiv:2505.08137*, arXiv, 13 May 2025. arXiv.org, [https://doi.org/10.48550/arXiv.2505.08137](https://doi.org/10.48550/arXiv.2505.08137).

**Zou, Qiang, et al.** “Intelligent CAD 2.0.” *arXiv:2410.03759*, arXiv, 2 Oct. 2024. arXiv.org, [https://doi.org/10.48550/arXiv.2410.03759](https://doi.org/10.48550/arXiv.2410.03759).
