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

We advanced the research on two complementary tracks. First, we conducted semi-structured interviews with four participants from different conflict contexts, spanning ages twenty to forty-six, to surface lived pain points and behavioral patterns. Second, we reviewed literature and public resources on mental-health needs and crisis logistics to calibrate beyond-sample trends. Synthesizing these inputs, several themes emerged. Conflict significantly increases the risk of anxiety, depression, and post-traumatic stress; during evacuation and blackout periods people want a “safe, always-available buffer” for emotions; essential information is scattered and of uncertain credibility, which amplifies panic; prolonged interruption of education and family routines deepens a sense of powerlessness. These insights defined the contours of need and established our baseline for evaluating concepts.

<img src="https://raw.githubusercontent.com/voiresa/Voiresa-homepage-HCI/main/static/assets/img/interview.png" alt="Project 1 Mindmap" style="width: 100%; height: auto; display: block; margin: 1rem auto; border-radius: 8px;">

##### PoVs

From coded interview material and secondary sources, we articulated three guiding point-of-view statements. First, people under war-related stress need an easily reachable, empathetic support tool that offers emotional relief at any moment. Second, residents in conflict zones need reliable, personalized guidance to navigate safety and displacement without worsening fear and confusion. Third, families in extreme circumstances need mechanisms to reconnect and trace loved ones to restore a sense of certainty and safety. These statements became our criteria for selecting and refining solutions.

##### Ideation

We generated three concept directions: a psychological support agent that functions even offline; a “calm dispatch” flow for evacuation safety; and a lead-aggregation system for family reconnection. Through rapid “speed-dating” evaluations with interviewees and a volunteer, we gathered immediate feedback on urgency, feasibility, and trust. The support agent consistently ranked as the most urgent and most deployable due to its high-frequency use cases and lower dependence on real-time data. Safety navigation and family tracing retained value for extreme scenarios, but their reliance on live data and strong privacy governance made near-term deployment harder. We therefore prioritized the support agent for prototyping.

##### System Design

The resulting solution is a mobile application that offers text and voice interaction, emphasizes cultural and age sensitivity, and includes an offline fallback. Architecturally, the front end provides a light-weight interface for dialogue, breathing exercises, mood journaling, and a “therapeutic space.” The back end manages input handling and task routing, calling networked large-language-model services when available and switching to a local model and curated prompt library when offline, ensuring continuity under unstable connectivity. To address acute risk, the agent incorporates safety triage to flag potential self-harm or violence, adapts conversation strategies accordingly, and suggests appropriate escalation or referral. Language and tone are tuned to remain calming, non-judgmental, and clear.

##### Prototype and Interaction Highlights

for our vertical design, the prompts are focused. Different cultural and age configurations trigger tailored prompting strategies and scripts. Speech recognition and synthesis complete a hands-free loop so users can engage without staring at the screen in dark or crowded settings. 

We also built a horizontal slice emphasizing conversational quality and the breathing-exercise flow, organized around a simple page sequence: Home, Breathing, Therapeutic Space, Mood Journal. The dialogue pathway supports multilingual use and seamless switching between text and voice. In connected states the system defaults to an online model; in weak or no-network conditions it falls back to local inference and precomposed responses to preserve essential support.

##### Usability Testing and Findings

We invited four participants aged twenty-one to twenty-three for scenario walk-throughs and short task trials, and collected Likert-scale ratings. Overall ease, confidence, and perceived safety averaged around 3.3, suggesting an early but promising experience. Consistency scored near 2.0, indicating stable behavior across screens. Willingness to use and learnability centered around 3.0, implying that value was understood while personalization and engagement could improve. Key issues included choppy chat scrolling, repetitive phrasing in the breathing coach, language settings that should apply globally, voice tone that could be gentler, and a desire for multiple “personas” to better match user preferences. In short, users validated the core promise of “offline-capable support,” and pointed to opportunities in personalization, interaction smoothness, and reliability.

##### Iteration Directions and Impact

Guided by feedback and the original need statements, the next phase focuses on three strands. First, deepen language, cultural, and age-specific configurations so dialogue and exercises are selected by user profile rather than one-size-fits-all heuristics. Second, improve long-dialogue memory and pacing, smooth scrolling and context carryover, and diversify the library of breathing and grounding routines. Third, strengthen risk stratification and referral pathways, offering clear “when and how to seek help” instructions offline and exploring low-friction handoffs to trusted volunteer networks or professional services when online. Evaluation will expand to larger samples and longer follow-ups to measure sustained effects on anxiety relief, sleep quality, and panic frequency.


#### Key Contributions:  
- I conducted four in-depth interviews and summarized insights from those interviews (not secondary research).

- Using open coding and thematic clustering, I distilled the conversations into clear themes and three point-of-view statements that guided our choices.

- I also co-designed key flows—conversation, breathing exercises, and mood journaling—while advocating for global language settings, gentler voice prosody, and a simple risk-tiering path. 
  

---

### **PROJECT3**  
**November 2025**  

Description.

#### Key Contributions:  
- I did...  
