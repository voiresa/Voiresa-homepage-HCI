### **PROJECT1: Aquatic-Friendly UST Campus**  
**September 2025**  

#### Project Description: 
This project is dedicated to designing and developing aquatic-friendly perspectives and solutions for students from the Aquatic Kingdom of Atlantics visiting HKUST. The initiative focuses on creating an inclusive, accessible, and welcoming environment that acknowledges and accommodates the unique physiological, cultural, and communicative needs of aquatic beings. Through a human-centered design approach, we aimed to reimagine campus facilities, social programs, and communication tools to ensure that every visiting student can fully participate in academic and cultural life while feeling respected and valued.


#### Key Contributions:  
- Researched aquatic students' needs and potential challenges before class to guide group discussion.

- Proposed solutions across three areas: environmental adaptation, language communication, and social inclusion.

- Collaborated on mind map development, improving structure and visual clarity.

<img src="https://raw.githubusercontent.com/voiresa/Voiresa-homepage-HCI/main/static/assets/img/project1.png" alt="Project 1 Mindmap" style="width: 100%; height: auto; display: block; margin: 1rem auto; border-radius: 8px;">

---

### **PROJECT2: APP Design for War-Affected Communities**  
**October 2025**  

#### Project Description:

This project addresses human–computer interaction design in communities affected by armed conflict. Our goal was to provide civilians living with elevated stress and intermittent connectivity a source of accessible, culturally sensitive, and emotionally stable psychological support. Early interviews and desk research showed an acute shortage of mental-health services, fragmented information channels, disrupted schooling and family ties, and persistent concerns about privacy and safety. Against this backdrop, we framed the design challenge as creating an offline-capable, trustworthy, and approachable support experience, delivered through a mobile voice-and-text agent.

##### Interviews and Key Insights

We advanced the research on two complementary tracks. First, we conducted semi-structured interviews with four participants from different conflict contexts, spanning ages twenty to forty-six, to surface lived pain points and behavioral patterns. 

<img src="https://raw.githubusercontent.com/voiresa/Voiresa-homepage-HCI/main/static/assets/img/interview.png" alt="Project 1 Mindmap" style="width: 80%; height: auto; display: block; margin: 1rem auto; border-radius: 8px;">

Second, we reviewed literature and public resources on mental-health needs and crisis logistics to calibrate beyond-sample trends. Synthesizing these inputs, several themes emerged. Conflict significantly increases the risk of anxiety, depression, and post-traumatic stress; during evacuation and blackout periods people want a “safe, always-available buffer” for emotions; essential information is scattered and of uncertain credibility, which amplifies panic; prolonged interruption of education and family routines deepens a sense of powerlessness. These insights defined the contours of need and established our baseline for evaluating concepts.

<img src="https://raw.githubusercontent.com/voiresa/Voiresa-homepage-HCI/main/static/assets/img/insights.png" alt="Project 1 Mindmap" style="width: 80%; height: auto; display: block; margin: 1rem auto; border-radius: 8px;">

##### PoVs

From coded interview material and secondary sources, we articulated three guiding point-of-view statements. 
- First, people under war-related stress need an easily reachable, empathetic support tool that offers emotional relief at any moment.
- Second, residents in conflict zones need reliable, personalized guidance to navigate safety and displacement without worsening fear and confusion.
- Third, families in extreme circumstances need mechanisms to reconnect and trace loved ones to restore a sense of certainty and safety. These statements became our criteria for selecting and refining solutions.

##### Ideation

We generated three concept directions: a psychological support agent that functions even offline; a “calm dispatch” flow for evacuation safety; and a lead-aggregation system for family reconnection. Through rapid “speed-dating” evaluations with interviewees and a volunteer, we gathered immediate feedback on urgency, feasibility, and trust. The support agent consistently ranked as the most urgent and most deployable due to its high-frequency use cases and lower dependence on real-time data. Safety navigation and family tracing retained value for extreme scenarios, but their reliance on live data and strong privacy governance made near-term deployment harder. We therefore prioritized the support agent for prototyping.

<img src="https://raw.githubusercontent.com/voiresa/Voiresa-homepage-HCI/main/static/assets/img/ideation.png" alt="Project 1 Mindmap" style="width: 80%; height: auto; display: block; margin: 1rem auto; border-radius: 8px;">

##### System Design

The resulting solution is a mobile application that offers text and voice interaction, emphasizes cultural and age sensitivity, and includes an offline fallback. Architecturally, the front end provides a light-weight interface for dialogue, breathing exercises, mood journaling, and a “therapeutic space.” The back end manages input handling and task routing, calling networked large-language-model services when available and switching to a local model and curated prompt library when offline, ensuring continuity under unstable connectivity. To address acute risk, the agent incorporates safety triage to flag potential self-harm or violence, adapts conversation strategies accordingly, and suggests appropriate escalation or referral. Language and tone are tuned to remain calming, non-judgmental, and clear.

<img src="https://raw.githubusercontent.com/voiresa/Voiresa-homepage-HCI/main/static/assets/img/design.png" alt="Project 1 Mindmap" style="width: 80%; height: auto; display: block; margin: 1rem auto; border-radius: 8px;">

##### Prototype and Interaction Highlights

For our vertical design, the prompts are focused. Different cultural and age configurations trigger tailored prompting strategies and scripts. Speech recognition and synthesis complete a hands-free loop so users can engage without staring at the screen in dark or crowded settings. 

<img src="https://raw.githubusercontent.com/voiresa/Voiresa-homepage-HCI/main/static/assets/img/prompt.png" alt="Project 1 Mindmap" style="width: 80%; height: auto; display: block; margin: 1rem auto; border-radius: 8px;">

We also built a horizontal slice emphasizing conversational quality and the breathing-exercise flow, organized around a simple page sequence: Home, Breathing, Therapeutic Space, Mood Journal. The dialogue pathway supports multilingual use and seamless switching between text and voice. In connected states the system defaults to an online model; in weak or no-network conditions it falls back to local inference and precomposed responses to preserve essential support.

<img src="https://raw.githubusercontent.com/voiresa/Voiresa-homepage-HCI/main/static/assets/img/horizontal.png" alt="Project 1 Mindmap" style="width: 80%; height: auto; display: block; margin: 1rem auto; border-radius: 8px;">

##### Usability Testing and Findings

We invited four participants aged twenty-one to twenty-three for scenario walk-throughs and short task trials, and collected Likert-scale ratings. Overall ease, confidence, and perceived safety averaged around 3.3, suggesting an early but promising experience. Consistency scored near 2.0, indicating stable behavior across screens. Willingness to use and learnability centered around 3.0, implying that value was understood while personalization and engagement could improve. Key issues included choppy chat scrolling, repetitive phrasing in the breathing coach, language settings that should apply globally, voice tone that could be gentler, and a desire for multiple “personas” to better match user preferences. In short, users validated the core promise of “offline-capable support,” and pointed to opportunities in personalization, interaction smoothness, and reliability.


#### Key Contributions:  
- I conducted four in-depth interviews and summarized insights from those interviews (not secondary research).

- Using open coding and thematic clustering, I distilled the conversations into clear themes and three point-of-view statements that guided our choices.

- I also co-designed key flows—conversation, breathing exercises, and mood journaling—while advocating for global language settings, gentler voice prosody, and a simple risk-tiering path. 
  
#### My Reflection:  
**My Reflection on This Project**

This work kept me close to people rather than neat frameworks. While synthesizing interview insights, I noticed how easily tidy categories can flatten messy, real emotions. I made a point to ground themes in participants’ own words, flag uncertainty, and treat every “insight” as something to be tested, not declared. Designing for unstable networks also reset my priorities. Reliability, gentle tone, and clear handoffs mattered more than clever features. The tension between warmth and safety stayed front and center: we want a human feel, but the system has to be honest about limits and make escalation unmistakably clear.

Looking ahead, my plan is straightforward. I want to widen the interview sample to include more age groups, languages, and cultural contexts, then pressure-test our core therapeutic loop with quick, low-overhead prototypes that run offline. I’ll add lightweight measures of momentary calm and perceived safety so we can track whether sessions actually help. On the design side, I plan to refine persona and tone settings, smooth long-dialogue memory and pacing, and expand the breathing and grounding library to reduce repetition. I also want to harden the risk-tiering path and map concrete referral options that work both offline and online, with privacy practices that are simple to understand. If these pieces come together, the agent should feel steadier, kinder, and more trustworthy exactly when people need it most.


---

### **PROJECT3: XR Design for couples in Long Distance Relationship**  
**November 2025**  

#### Project Description:
This project addresses the experience of long-distance relationships among university students living across cities and time zones, particularly in the context of increasing mobility, migration, and study-abroad trends. Our goal was to reimagine how Social XR could foster a stronger sense of shared presence, emotional closeness, and everyday intimacy for couples who feel disconnected by physical distance and fragmented schedules. Interviews and speeddating sessions revealed that while students rely heavily on video calls and messaging, these tools fail to recreate the feeling of truly “being together,” often leading to loneliness, misaligned expectations, and a lack of shared routines. Participants expressed a desire for more immersive yet lightweight solutions that remain affordable, natural, and privacy-conscious

##### Interviews and Key Insights
We conducted semi-structured interviews with seven university students across different relationship statuses, including those in long-distance relationships and those considering study or migration abroad. We also reviewed broader trends in student mobility and long-distance relationship dynamics. 


Key findings showed that while video calls and messaging remain primary communication tools, they fail to create emotional closeness or shared presence. Participants reported loneliness, fragmented routines, and a lack of meaningful co-experiences, but expressed interest in XR solutions that are immersive, affordable, and natural. The core desire was not just communication, but the feeling of “living together” despite distance.

##### PoVs
From the research, we defined three guiding points of view:

- Long-distance couples need ways to feel emotionally and physically close beyond basic communication tools.

- Partners across time zones require asynchronous interaction that still conveys care and presence.

- Couples need a shared digital space that grows with their relationship to foster belonging and continuity.


##### Ideation
We explored multiple concepts including VR shared spaces, haptic suits, reconciliation environments, and AR companions. Through speed-dating evaluations, the VR shared space emerged as the most meaningful but needed to remain affordable and lightweight. We therefore integrated immersive co-creation with asynchronous features and virtual pet bonding, forming the final concept: EverPresence.


##### Prototype and Interaction Highlights

The prototype focused on two levels of experience: immersion and emotional trace. In the vertical slice, users enter a customizable virtual home, name and care for a shared pet, and interact with decorative objects that visually evolve over time. These interactions simulate cohabitation and shared responsibility.

The horizontal slice emphasized the memo system and asynchronous cues. Partners can leave notes, reactions, or symbolic items that appear in the shared environment and persist as emotional markers. These moments reinforce continuity even when interaction is not simultaneous.

User pathways were designed around simplicity: entering the shared space, interacting with the pet, placing or responding to memos, and customizing the environment. These flows aim to transform routine digital communication into a living, shared narrative.

##### Usability Testing and Findings
User testing showed strong emotional appeal and natural interaction, but highlighted areas for improvement such as avatar design, interaction clarity, pet responsiveness, and platform stability. Despite limitations, participants validated the concept’s potential to enhance emotional closeness.



#### Key Contributions:  
- Synthesized interview insights into core themes and PoVs

- Co-developed interaction flows for shared spaces and pet bonding

- Contributed to usability testing analysis and design refinement
  
#### My Reflection:  
**My Reflection on This Project**




#### Key Contributions:  
- I did...  
