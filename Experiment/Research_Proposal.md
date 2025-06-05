# One Soul, Many Forms: Influence of Identity Continuity in Virtual Agents
## Abstract
This proposal investigates how maintaining a consistent identity across multiple virtual agent embodiments affects user experience in VR. We will study whether identity continuity (one agent persona with changing form) versus identity discontinuity (different personas in each form) alters users’ rapport, emotional connectedness, and perceived credibility. Four VR scenarios with different agent forms (human avatar, animal companion, embodied object, voice-only) will be used. In a controlled between-subject design, participants will experience both continuity conditions. Rapport and connectedness will be measured quantitatively via validated Likert scales (HARQ and ASAQ), while credibility will be assessed qualitatively through post-experience interviews
We hypothesize that continuous identity yields higher rapport and connectedness than discontinuous identity.Expected findings will deepen theory on agent persona design and offer practical guidelines for VR agent development.

## 1. Introduction

Virtual reality (VR) enables immersive interactions with virtual agents of various forms [^1]. As virtual agents move across platforms, devices, and forms, it’s important to help users still feel like they’re interacting with the same agent and this study explores how to make that work in a way people can connect with. These agents can appear as human-like avatars, animals, objects, or even disembodied voices. A key open question is whether users perceive these different forms as one individual agent or as separate entities, and how that perception influences the social bond[^2]. We term this factor identity continuity: whether an agent’s identity is preserved across form changes. Maintaining identity continuity could strengthen the user’s sense of an ongoing relationship; breaking it might hinder rapport. This study asks: Does maintaining **identity continuity** in virtual agents with changing appearances help users maintain or **strengthen** their sense of **rapport**, **emotional connectedness** and **credibility** in **VR GAMES**?

This question addresses a gap in HCI/VR research. Previous work has explored agent embodiment[^3] [^12] [^9] and social presence[^4], but seldom the effect of persona consistency across form changes. Rapport (moment-to-moment interaction quality) and emotional connectedness (deeper sense of closeness) are critical for trust and engagement in human-agent interaction. For example, rapport is “a state marked by mutual attentiveness, positivity, and coordination” [^5], while connectedness involves viewing the agent as part of one’s social circle[^6]. Yet it is unclear if shifting a virtual agent’s appearance (from a guide avatar to a companion dog, etc.) disrupts these bonds. Our motivation is twofold: theoretically, we will extend understanding of identity and social bonding in VR; practically, we will inform VR developers how to design agent identities for better user experience. If continuity matters, developers should keep persona cues consistent; if not, more flexibility is possible. This proposal outlines a systematic experiment to test these ideas.

## 2. Literature Review
### 2.1 Virtual Agents in VR
Virtual agents are broadly defined as computer-generated characters that engage users in lifelike interactions within a digital environment[^7]. These agents, ranging from simple chatbots to richly animated 3D avatars, typically assume social roles (e.g. guide, companion, or adversary) that shape the user’s experience or narrative[^8]. Crucially, embodied agents can employ nonverbal cues (gesture, gaze, posture) to enrich communication. Prior work has shown that simply giving an agent a humanlike form causes users to treat it more like "another person" and that adding natural behaviors (e.g. expressive gestures or emotion) increases users' perceptions of the agent's realism and likability[^9]. Likewise, agents combining verbal and visual channels tend to elicit a strong sense of social presence, users often mindlessly apply social norms to them as if they were real humans[^10] [^11]. As a result, virtual agents are a major focus of HCI research: for example, disembodied voice assistants such as Siri and Alexa already have on the order of hundreds of millions of users worldwide[^13]. In practice, virtual agents have been deployed to support learning, therapy, or collaboration, and studies report that embodied agents in VR can even reduce user cognitive load[^14], and improve engagement and task performance by boosting immersion and rapport[^15].
In immersive VR specifically, agents serve as social partners or guides in highly realistic settings. The strong sense of presence induced by VR means that users react very authentically to virtual humans and environments[^16] [^17], so the design of an agent's form can have a pronounced impact on user experience. To cover the relevant design space, we select four representative agent embodiments. First, a fully embodied humanlike agent allows use of gaze and gesture, for example, 'Jake' agent was given head turns and hand waves to enhance perceived helpfulness and trust[^10]. Second, an animal-companion agent is included: virtual animals (pets) are known to evoke empathy and social support, and studies even propose VR dogs as walking companions to reduce loneliness[^18]. Third, an object-based agent (for example, a talking 'smart speaker' avatar) embodies an agent in a familiar object: prior AR work modeled a cylindrical smart-home device ('Zee') representing an Alexa-like agent[^10]. Finally, a voice-only agent (no visual form) represents the common disembodied assistants ('Ava', similar to Siri)[^10]. These four forms match those used in related studies – e.g. Ruiz et al. explicitly compared a voice-only assistant, a smart speaker cylinder, a full-size avatar and a miniature avatar in an AR task and each has been shown to produce distinct user responses (different gaze patterns, trust levels) in prior work[^10]. By testing these four modalities together, we ensure our experiments span the key variations of embodiment and anthropomorphism that HCI theory suggests will affect social and experiential outcomes in VR.

### 2.2 Identity Continuity
In human–computer interaction, an agent’s identity cues (name, voice, color scheme) shape user perceptions[^19]. In narrative theory and psychology, maintaining a consistent character across scenes strengthens the user’s sense of continuity[^20]. For example, in storytelling or game design, a character’s persistent identity often yields greater emotional investment[^21]. However, little prior work has examined identity consistency across multi-form agents in VR. Existing immersive virtual environments research has examined agent embodiment (e.g. how animal vs. human agents influence empathy) and social presence, but typically with a single agent form[^22]. Studies on robot consistency show that repeated interactions with the same persona can build trust, while changing persona might confuse users. We draw on analogous findings from social robot research (e.g. user trust in physically embodied agents) to posit that identity continuity in VR will similarly affect relational outcomes.

### 2.3 Rapport, Emotional Connectedness and Credibility. 
- Rapport refers to the immediate quality of interaction: the feeling that communication is smooth and coordinated. Tickle-Degnen and Rosenthal define rapport as mutual attentiveness, positivity, and coordination. In VR, high rapport might manifest as users feeling “in sync” with an agent’s dialogue or actions.
- Emotional connectedness is a longer-term bond: how much the agent feels like part of the user’s social circle. Aron et al. note that closeness “exists when a person’s representation of self includes the other”. In our context, connectedness reflects how much a user feels allied with the agent across scenes. We expect that rapport can fluctuate scene-to-scene, while connectedness accumulates over the experiment. High rapport often precedes trust, whereas high connectedness coexists with deep trust.
- Credibility captures whether users regard the agent as a reliable and competent partner capable of performing the task at hand. McGloin et al. operationalise credibility with bipolar adjectives such as unreliable–reliable, incompetent–competent and untrustworthy–trustworthy applied to an avatar or message source. More broadly, credibility is “a set of source characteristics that increase confidence and trust in the message”. In work on explainable AI, Hoffman et al. incorporate similar notions—confidence, predictability, reliability and believability—into the XAI Trust Scale, framing credibility as the user’s judgment that the system will act correctly and consistently.


Together, these three constructs give a layered view of the user–agent relationship: rapport captures the felt smoothness of each encounter, emotional connectedness reflects the accumulating social bond, and credibility gauges whether the agent is considered competent and dependable enough to achieve the user’s goals.

### 2.4 Literature Synthesis and Research Gap 

Prior HCI studies have explored how different agent embodiments and behaviors affect user experience. For example, research on companion agents (both human and animal) suggests that social presence and realism enhance engagement. However, most VR agent studies use a single avatar type. Studies on nonverbal communication in VR show that consistent cues (like voice and style) help users follow an agent’s intentions. In related work, an “artificial social agent questionnaire” (ASAQ) was developed to measure users’ sense of social bond with an agent. These ASAQ constructs (e.g. willingness to interact, perceived social presence) inform our connectedness measure. Our review indicates a gap: few studies have manipulated agent identity continuity explicitly. We aim to fill this gap by comparing identity-continuous vs discontinuous conditions, leveraging a mixed-agent VR setting. This will extend theory on identity design: if our results support continuity, it implies that users form a single “virtual persona” that spans forms, enriching theories of multi-agent interaction in VR.



## 3. Research Questions and Hypotheses

Based on the above, our primary Research Question is: Does maintaining **identity continuity** in virtual agents with changing appearances help users maintain or **strengthen** their sense of **rapport**, **emotional connectedness** and **credibility** in **VR GAMES**? We propose two main hypotheses:
- **H1 (Rapport): Participants in the identity-continuous condition will report higher rapport scores than in the identity-discontinuous condition.**
- **H2 (Emotional Connectedness): Participants in the identity-continuous condition will report higher emotional connectedness scores than in the identity-discontinuous condition.**
- **H3 (Credibility): Participants in the identity-continuous condition will report higher credibility scores than in the identity-discontinuous condition.**

These are directional hypotheses based on the assumption that continuity fosters social bond.


## 4. Research Design
### 4.1 Methodology


To effectively assess the influence of identity continuity on rapport, emotional connectedness, and agent credibility, this study will employ a between-subjects experimental design. Participants will be randomly assigned to one of two experimental conditions:
- **C1: Identity-Discontinuous Condition: Participants interact with agents that exhibit distinct identity cues in each of the four VR scenarios.**
- **C2: Identity-Continuous Condition: Participants interact with virtual agents maintaining consistent identity cues across all four VR scenarios (Embodied Human, Animal Companion, Object-Based AI, Voice-Only).**

This between-subject approach was selected based on careful consideration of its advantages and limitations. Specifically, this design eliminates potential carryover or order effects associated with repeated measures. Participants engage in only four VR interactions, significantly reducing fatigue and the risk of VR-induced motion sickness compared to a within-subject design requiring eight interactions. Additionally, a simpler experimental setup reduces logistical complexity and avoids participant hypothesis guessing about experimental conditions. Furthermore, demographic data (age, gender, VR experience) will be collected to verify group equivalence, thus ensuring comparability between the two experimental conditions.All other aspects, such as VR scene content, duration, complexity, and interaction methods, will remain standardized across both conditions to isolate identity continuity as the independent variable influencing user rapport, emotional connectedness and credibility (quantitatively measured via validated scales).

### 4.2 Participants
- **Sample size**
- **Recruitment**
- **Assignment**


### 4.3 Experimental Conditions

We have two Identity Continuity conditions：

- **C1: Identity-Discontinuous Condition: Participants interact with agents that exhibit distinct identity cues in each of the four VR scenarios.**
- **C2: Identity-Continuous Condition: Participants interact with virtual agents maintaining consistent identity cues across all four VR scenarios (Embodied Agent, Animal Companion, Object-Based Agent, Voice-Only Agent).**

**Agent Forms (Scenes)**: Each scene has a different agent embodiment to test multi-form identity. The four scenes (used in both conditions) are:
- **Escape Room — Embodied Agent**  
  You stand in a locked puzzle chamber. A humanoid companion shares the space, pointing out clues, offering verbal hints, and reacting to your progress. With VR hands you grab, rotate, and combine objects until the exit door unlocks.

- **The World Beyond — Animal Companion**  
  A mixed-reality creature named Oppy follows you around your real room. Using a magic flashlight, you reveal glowing orbs behind virtual “portals,” toss them to Oppy, and guide it with simple gestures or voice commands as it responds playfully.

- **Phanto — Object-Based Agent (Talking Gun)**  
  Your sidekick is the Polterblast 3000—a sentient ghost-blaster that chats like a *Rick and Morty* gag where the gun has Morty’s personality. It cracks jokes, warns of phantoms, and coaches your aim while you spray ectoplasmic goo and vacuum it back up.

- **Whisperer — Voice-Only Agent**  
  No avatar appears. An unseen “translator” whispers riddles and clues. You reply aloud; the environment changes according to recognized intents. The agent exists purely as a disembodied voice that mediates the interaction.

Each participant experiences all four scenes. In the C2 (identity-continuous condition), the same agent appears in different guises (human, animal, object, voice) with consistent cues. In the C1 (identity-discontinuous condition), the agent key features changes each scene indicating a different persona. The order of scenes is fixed (1→4) for all participants to maintain flow.

### 4.4 Data Collection

After each scene interaction, participants will complete two questionnaires on a computer:
- Rapport: Measured via the Human–Agent Rapport Questionnaire (HARQ) on a 7-point Likert scale. The HARQ includes items about how natural and positive the interaction felt.
- Emotional Connectedness: Measured via the Artificial Social Agent Questionnaire (ASAQ) adapted for connectedness, also on 7-point scales.The ASAQ asks about users’ perceived closeness and willingness to interact with the agent.
- Credibility: Measured via the Trust Scale adapted for credibility, 5-point scales. 

These instruments have been previously validated. All measures are administered immediately after each of the four scenes.

### 4.5 Data Analysis
- **Quantitative Analysis**:
Given the between-subjects design, we will analyze the quantitative data (rapport, emotional connectedness and credibility) using Unpaired t-tests (or Mann-Whitney U tests if normality assumptions are violated). Specifically, we will compare mean scores for rapport, emotional connectedness and credibility between the Identity-Continuous and Identity-Discontinuous conditions. Each participant’s scores will be averaged across the four VR agent forms to yield a composite measure per participant. Based on our hypotheses, we anticipate significantly higher rapport, emotional connectedness and credibility scores in the Identity-Continuous condition compared to the Identity-Discontinuous condition.

- **Qualitative Analysis**:

## 5. Expected Results and Contributions

We anticipate that participants will report significantly higher rapport connectedness and credibility in the identity-continuous condition. In other words, H1, H2 and H3 are expected to be supported: continuous identity will foster smoother interactions and a deeper bond than when the agent “resets” persona each scene. For example, keeping the same name, voice and memory may help users feel an ongoing partnership, consistent with the notion that connectedness develops over repeated interactions. By contrast, in the discontinuous condition the break in identity may act like a scene change, preventing cumulative bond formation. Continuous identity may lead users to perceive the agent as more reliable and coherent, whereas discontinuity might introduce doubt (e.g., “Why is this new voice here?”). These insights will extend theoretical understanding of agent design by showing that identity design, not just visual fidelity or behavior influences social metrics. This complements existing HCI theories on trust and anthropomorphism, adding empirical evidence about persona continuity. We effectively test that a single persona transcending form enhances user–agent rapport.

Practically, the results will provide design guidelines for VR developers. If continuity proves beneficial, designers should ensure that characters retain key identity markers across different contexts or appearances. For instance, a tutorial agent that later becomes an in-game companion should keep a recognizable name and voice to leverage established rapport. Such guidelines can improve user experience in VR games, training, and social simulations. On the other hand, if discontinuity shows little effect or even benefits (e.g., novelty reduces rapport but adds intrigue), designers might instead vary agents freely. We will articulate these implications clearly: for example, “Use consistent naming and vocal cues for an agent that appears in multiple forms to maximize emotional engagement” (if supported by data).

Finally, this study approach contributes to research methodology in VR as well. By combining between-subject design, we offer a template for future multi-agent experiments. Overall, we expect to contribute both empirically and practically to the field of HCI and VR agent design.


## 6. References
[^1]:  Fox, J., Ahn, S. J., Janssen, J. H., Yeykelis, L., Segovia, K. Y., and Bailenson, J. N. (2015). Avatars versus Agents: A Meta-Analysis Quantifying the Effect of Agency on Social Influence. Human-Computer Interact. 30, 401–432. doi:10.1080/07370024.2014.921494

[^2]:  Greenberg, N., & Walker, C. (2024). Lessons from an app update at Replika AI: Identity discontinuity and user backlash (arXiv 2412.14190).

[^3]: D. A. Robb, J. Lopes, M. I. Ahmad, P. E. Mckenna, S. Liu, K. Lohan, H. Hastie (2023). Seeing eye to eye: trustworthy embodiment for task-based conversational agents. Sec. Human-Robot Interaction. doi:10.3389/frobt.2023.1234767

[^4]: Catherine S. Oh, J. N. Bailenson, G. F. Welch. (2018). A Systematic Review of Social Presence: Definition, Antecedents, and Implications. Sec. Virtual Environments. Virtual Human Interaction Lab, Department of Coomunication, Standford University. doi: 10.3389/frobt.2018.00114  

[^5]: T. Bickmore and R. Picard. (2005). Establishing and maintaining long-term humancomputer relationships. ACM Transactions on Computer-Human Interaction (TOCHI) 12, 2 (2005), 293–327. doi: 10.1145/1067860.106786

[^6]: Aron, A., Aron, E. N., Tudor, M., & Nelson, G. (1991). Close relationships as including other in the self. Journal of Personality and Social Psychology, 60(2), 241–253. doi: 10.1037/0022-3514.60.2.241

[^7]: R.Poievt (2023),  Virtual Agent's perceived intelligence and believability in video games: Exploring the relation between design factors and players' expectations.

[^8]: B. Lugrin. (2021). Introduction to Socially Interactice Agents. The Handbook on Socially Interactive Agents: 20 years of Research on Embodied Conversational Agents, Intelligent Virtual Agents, and Social Robotics Volume 1: Methods, Behavior, Cognition. doi: 10.1145/3477322.34773

[^9]: C. Becker, S. Kopp, and I. Wachsmuth. (2007). Why emotions should be integrated into conversational agents. Conversational informatics: an engineering approach: 49–68. doi: 10.1002/9780470512470.ch3


[^10]: I. Wang, J. Smith and J. Ruiz, " Exploring Virtual Agents for Augmented Reality" in Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems, Glasgow, U.K., May 2 2019, Paper 281, doi: 10.1145/3290605.3300511.

[^11]: C. Nass, J. Steuer, and E. R. Tauber. (1994). Computers Are Social Actors. In Proceedings of the SIGCHI Conference on Human Factors in Computing Systems (CHI '94), 72–78. doi: 10.1145/191666.19170

[^12]: S. Andrist, M. Gleicher, and B. Mutlu. (2017). Looking Coordinated: Bidirectional Gaze Mechanisms for Collaborative Interaction with Virtual Characters. In Proceedings of the 2017 CHI Conference on Human Factors in Computing Systems (CHI '17), 2571–2582. doi: 10.1145/3025453.3026033

[^13]: K. Wagner and H. Schramm-Klein. (2019).  Alexa, Are You Human? Investigating Anthropomorphism of Digital Voice Assistants – A Qualitative Approach. ICIS 2019 Proceedings. 7. https://aisel.aisnet.org/icis2019/human_computer_interact/human_computer_interact/7

[^14]: Kim, K., de Melo, C. M., Norouzi, N., Bruder, G., and Welch, G. F. (2020). “Reducing task load with an embodied intelligent virtual assistant for improved performance in collaborative decision making,” in 2020 IEEE Conference on Virtual Reality and 3D User Interfaces (VR), Atlanta, Georgia, America, March 22–26, 2020 (IEEE), 529–538.

[^15]: de Melo, C. M., Kim, K., Norouzi, N., Bruder, G., and Welch, G. (2020). Reducing cognitive load and improving warfighter problem solving with intelligent virtual assistants. Front. Psychol. 11, 554706. doi:10.3389/fpsyg.2020.554706

[^16]: Hoppe, M., Rossmy, B., Neumann, D. P., Streuber, S., Schmidt, A., and Machulla, T.-K. (2020). “A human touch: social touch increases the perceived human-likeness of agents in virtual reality,” in Proceedings of the 2020 CHI conference on human factors in computing systems, 1–11. doi:10.1145/3313831.3376719
[^17]: Griol, D., Sanchis, A., Molina, J. M., and Callejas, Z. (2019). Developing enhanced conversa  tional agents for social virtual worlds. Neurocomputing 354, 27–40. doi:10.1016/j.neucom.2018.09.099

[^18]: Z. Momand. J. H. Chan and P. Mongkolnam. (2023). Immersive Technologies in Virtual Companions: A Systematic Literature Review. Human-Computer Interaction (cs.HC). doi: 10.48550/arXiv.2309.01214

[^19]: E. Gu and S. S. Sundar. (2019). Humanizing chatbots: The effects of visual, identity and conversational cues on humanness perceptions. Computers in Human Behavior. doi: 10.1016/j.chb.2019.01.020

[^20]: Zwaan, R. A., Langston, M. C., & Graesser, A. C. (1995). The Construction of Situation Models in Narrative Comprehension: An Event-Indexing Model. Psychological Science, 6(5), 292–297. http://www.jstor.org/stable/40063035

[^21]: Melanie C. and GreenTimothy C. Brock. (2000). The Role of Transportation in the Persuasiveness of Public Narrative. Journal of Personality and Social Psychology. 79(5):701-21. doi：10.1037/0022-3514.79.5.701

[^22]: Sun Joo (Grace) Ahn, Joshua Bostick, Elise Ogle, Kristine L. Nowak, Kara T. McGillicuddy, Jeremy N. Bailenson, Experiencing Nature: Embodying Animals in Immersive Virtual Environments Increases Inclusion of Nature in Self and Involvement with Nature, Journal of Computer-Mediated Communication, Volume 21, Issue 6, 1 November 2016, Pages 399–419, doi: 10.1111/jcc4.12173




