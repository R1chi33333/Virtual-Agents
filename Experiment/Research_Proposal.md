# One Soul, Many Forms: Influence of Identity Continuity in Virtual Agents
## Abstract
This proposal investigates how maintaining a consistent identity across multiple virtual agent embodiments affects user experience in VR. We will study whether identity continuity (one agent persona with changing form) versus identity discontinuity (different personas in each form) alters users’ rapport, emotional connectedness, and perceived credibility. Four VR scenarios with different agent forms (human avatar, animal companion, embodied object, voice-only) will be used. In a controlled between-subject design, participants will experience both continuity conditions. Rapport and connectedness will be measured quantitatively via validated Likert scales (HARQ and ASAQ), while credibility will be assessed qualitatively through post-experience interviews
We hypothesize that continuous identity yields higher rapport and connectedness than discontinuous identity.Expected findings will deepen theory on agent persona design and offer practical guidelines for VR agent development.

## 1. Introduction

Virtual reality (VR) enables immersive interactions with virtual agents of various forms. As virtual agents move across platforms, devices, and forms, it’s important to help users still feel like they’re interacting with the same agent and this study explores how to make that work in a way people can connect with. These agents can appear as human-like avatars, animals, objects, or even disembodied voices. A key open question is whether users perceive these different forms as one individual agent or as separate entities, and how that perception influences the social bond. We term this factor identity continuity: whether an agent’s identity is preserved across form changes. Maintaining identity continuity could strengthen the user’s sense of an ongoing relationship; breaking it might hinder rapport. This study asks: Does maintaining **identity continuity** in virtual agents with changing appearances help users maintain or **strengthen** their sense of **rapport**, **emotional connectedness** and **credibility** in **VR GAMES**?

This question addresses a gap in HCI/VR research. Previous work has explored agent embodiment and social presence, but seldom the effect of persona consistency across form changes. Rapport (moment-to-moment interaction quality) and emotional connectedness (deeper sense of closeness) are critical for trust and engagement in human-agent interaction. For example, rapport is “a state marked by mutual attentiveness, positivity, and coordination”, while connectedness involves viewing the agent as part of one’s social circle. Yet it is unclear if shifting a virtual agent’s appearance (from a guide avatar to a companion dog, etc.) disrupts these bonds. Our motivation is twofold: theoretically, we will extend understanding of identity and social bonding in VR; practically, we will inform VR developers how to design agent identities for better user experience. If continuity matters, developers should keep persona cues consistent; if not, more flexibility is possible. This proposal outlines a systematic experiment to test these ideas.

## 2. Literature Review
### 2.1 Virtual Agents in VR
- "Virtual agents in HCI are broadly defined as computer-generated characters that engage users in lifelike interactions within a digital environment"[]. These agents, ranging from simple chatbots to richly animated 3D avatars – typically assume social roles (e.g. guide, companion, or adversary) that shape the user’s experience or narrative[]. Crucially, embodied agents can employ nonverbal cues (gesture, gaze, posture) to enrich communication: prior work has shown that simply giving an agent a humanlike form causes users to treat it more like "another person" and that adding natural behaviors (e.g. expressive gestures or emotion) increases users' perceptions of the agent's realism and likability[]. Likewise, agents combining verbal and visual channels tend to elicit a strong sense of social presence, users often mindlessly apply social norms to them as if they were real humans[][]. As a result, virtual agents are a major focus of HCI research: for example, disembodied voice assistants such as Siri and Alexa already have on the order of hundreds of millions of users worldwide[]. In practice, virtual agents have been deployed to support learning, therapy, or collaboration, and studies report that embodied agents in AR/VR can even reduce user cognitive load and improve engagement and task performance by boosting immersion and rapport.

- In immersive VR specifically, agents serve as social partners or guides in highly realistic settings. The strong sense of presence induced by VR means that users react very authentically to virtual humans and environments[][], so the design of an agent's form can have a pronounced impact on user experience. To cover the relevant design space, we select four representative agent embodiments. First, a fully embodied humanlike agent allows use of gaze and gesture, for example, 'Jake' agent was given head turns and hand waves to enhance perceived helpfulness and trust[]. Second, an animal-companion agent is included: virtual animals (pets) are known to evoke empathy and social support, and studies even propose AR/VR dogs as walking companions to reduce loneliness[]. Third, an object-based agent (for example, a talking 'smart speaker' avatar) embodies an agent in a familiar object: prior AR work modeled a cylindrical smart-home device ('Zee') representing an Alexa-like agent[]. Finally, a voice-only agent (no visual form) represents the common disembodied assistants ('Ava', similar to Siri). These four forms match those used in related studies – e.g. Ruiz et al. explicitly compared a voice-only assistant, a smart-speaker cylinder, a full-size avatar and a miniature avatar in an AR task and each has been shown to produce distinct user responses (different gaze patterns, trust levels) in prior work. By testing these four modalities together, we ensure our experiments span the key variations of embodiment and anthropomorphism that HCI theory suggests will affect social and experiential outcomes in VR.

### 2.2 Identity Continuity
In human–computer interaction, an agent’s identity cues (name, voice, color scheme) shape user perceptions. In narrative theory and psychology, maintaining a consistent character across scenes strengthens the user’s sense of continuity. For example, in storytelling or game design, a character’s persistent identity often yields greater emotional investment. However, little prior work has examined identity consistency across multi-form agents in VR. Existing VR research has examined agent embodiment (e.g. how animal vs. human agents influence empathy) and social presence, but typically with a single agent form. Studies on robot consistency show that repeated interactions with the same persona can build trust, while changing persona might confuse users. We draw on analogous findings from social robot research (e.g. user trust in physically embodied agents) to posit that identity continuity in VR will similarly affect relational outcomes.

### 2.3 Rapport vs. Emotional Connectedness. 
These are distinct but related constructs. Rapport refers to the immediate quality of interaction: the feeling that communication is smooth and coordinated. Tickle-Degnen and Rosenthal define rapport as mutual attentiveness, positivity, and coordination. In VR, high rapport might manifest as users feeling “in sync” with an agent’s dialogue or actions. Emotional connectedness (or closeness) is a longer-term bond: how much the agent feels like part of the user’s social circle. Aron et al. note that closeness “exists when a person’s representation of self includes the other”. In our context, connectedness reflects how much a user feels allied with the agent across scenes. We expect that rapport can fluctuate scene-to-scene, while connectedness accumulates over the experiment. High rapport often precedes trust, whereas high connectedness coexists with deep trust (building on literature in trust and virtual agents.

### 2.4 Literature Synthesis and Research Gap 

Prior HCI studies have explored how different agent embodiments and behaviors affect user experience. For example, research on companion agents (both human and animal) suggests that social presence and realism enhance engagement. However, most VR agent studies use a single avatar type. Studies on nonverbal communication in VR show that consistent cues (like voice and style) help users follow an agent’s intentions. In related work, an “artificial social agent questionnaire” (ASAQ) was developed to measure users’ sense of social bond with an agent. These ASAQ constructs (e.g. willingness to interact, perceived social presence) inform our connectedness measure. Our review indicates a gap: few studies have manipulated agent identity continuity explicitly. We aim to fill this gap by comparing identity-continuous vs discontinuous conditions, leveraging a mixed-agent VR setting. This will extend theory on identity design: if our results support continuity, it implies that users form a single “virtual persona” that spans forms, enriching theories of multi-agent interaction in VR.



## 3. Research Questions and Hypotheses

Based on the above, our primary Research Question is: Does maintaining **identity continuity** in virtual agents with changing appearances help users maintain or **strengthen** their sense of **rapport**, **emotional connectedness** and **credibility** in **VR GAMES**? We propose two main hypotheses:
- **H1 (Rapport): Participants in the identity-continuous condition will report higher rapport scores than in the identity-discontinuous condition.**
- **H2 (Connectedness): Participants in the identity-continuous condition will report higher emotional connectedness scores than in the identity-discontinuous condition.**

These are directional hypotheses based on the assumption that continuity fosters social bond. Credibility will be explored qualitatively via interview, so we do not state a directional hypothesis for it. We will nonetheless examine user remarks on credibility in the exit interview to see if continuity affects those perceptions (beyond just rapport and closeness).



## 4. Research Design
### 4.1 Methodology


To effectively assess the influence of identity continuity on rapport, emotional connectedness, and agent credibility, this study will employ a between-subjects experimental design. Participants will be randomly assigned to one of two experimental conditions:
- **C1: Identity-Continuous Condition: Participants interact with virtual agents maintaining consistent identity cues across all four VR scenarios (Embodied Human, Animal Companion, Object-Based AI, Voice-Only).**
- **C2: Identity-Discontinuous Condition: Participants interact with agents that exhibit distinct identity cues in each of the four VR scenarios.**

This between-subject approach was selected based on careful consideration of its advantages and limitations. Specifically, this design eliminates potential carryover or order effects associated with repeated measures. Participants engage in only four VR interactions, significantly reducing fatigue and the risk of VR-induced motion sickness compared to a within-subject design requiring eight interactions. Additionally, a simpler experimental setup reduces logistical complexity and avoids participant hypothesis guessing about experimental conditions. Furthermore, demographic data (age, gender, VR experience) will be collected to verify group equivalence, thus ensuring comparability between the two experimental conditions.All other aspects, such as VR scene content, duration, complexity, and interaction methods, will remain standardized across both conditions to isolate identity continuity as the independent variable influencing user rapport, emotional connectedness (quantitatively measured via validated scales), and credibility (qualitatively assessed through semi-structured interviews).

### 4.2 Participants
- **Sample size**
- **Recruitment**
- **Assignment**


### 4.3 Experimental Conditions

We have two Identity Continuity conditions：

- **C1: Identity-Continuous Condition: Participants interact with virtual agents maintaining consistent identity cues across all four VR scenarios (Embodied Agent, Animal Companion, Object-Based Agent, Voice-Only Agent).**
- **C2: Identity-Discontinuous Condition: Participants interact with agents that exhibit distinct identity cues in each of the four VR scenarios.**

**Agent Forms (Scenes)**: Each scene has a different agent embodiment to test multi-form identity. The four scenes (used in both conditions) are:
- **Escape Room — Embodied Agent**  
  You stand in a locked puzzle chamber. A humanoid companion shares the space, pointing out clues, offering verbal hints, and reacting to your progress. With VR hands you grab, rotate, and combine objects until the exit door unlocks.

- **The World Beyond — Animal Companion**  
  A mixed-reality creature named Oppy follows you around your real room. Using a magic flashlight, you reveal glowing orbs behind virtual “portals,” toss them to Oppy, and guide it with simple gestures or voice commands as it responds playfully.

- **Phanto — Object-Based Agent (Talking Gun)**  
  Your sidekick is the Polterblast 3000—a sentient ghost-blaster that chats like a *Rick and Morty* gag where the gun has Morty’s personality. It cracks jokes, warns of phantoms, and coaches your aim while you spray ectoplasmic goo and vacuum it back up.

- **Whisperer — Voice-Only Agent**  
  No avatar appears. An unseen “translator” whispers riddles and clues. You reply aloud; the environment changes according to recognized intents. The agent exists purely as a disembodied voice that mediates the interaction.

Each participant experiences all four scenes. In the C1 (identity-continuous condition), the same agent appears in different guises (human, animal, object, voice) with consistent cues. In the C2 (identity-discontinuous condition), the agent key features changes each scene indicating a different persona. The order of scenes is fixed (1→4) for all participants to maintain flow.

### 4.4 Data Collection

After each scene interaction, participants will complete two questionnaires on a computer:
- Rapport: Measured via the Human–Agent Rapport Questionnaire (HARQ) on a 7-point Likert scale. The HARQ includes items about how natural and positive the interaction felt.
- Emotional Connectedness: Measured via the Artificial Social Agent Questionnaire (ASAQ) adapted for connectedness, also on 7-point scales.The ASAQ asks about users’ perceived closeness and willingness to interact with the agent.

These instruments have been previously validated. Both measures are administered immediately after each of the four scenes.

### 4.5 Data Analysis
- **Quantitative Analysis**:
Given the between-subjects design, we will analyze the quantitative data (rapport and emotional connectedness) using Unpaired t-tests (or Mann-Whitney U tests if normality assumptions are violated). Specifically, we will compare mean scores for rapport and emotional connectedness between the Identity-Continuous and Identity-Discontinuous conditions. Each participant’s scores will be averaged across the four VR agent forms to yield a composite measure per participant. Based on our hypotheses, we anticipate significantly higher rapport and emotional connectedness scores in the Identity-Continuous condition compared to the Identity-Discontinuous condition.

- **Qualitative Analysis**:

## 5. Expected Results and Contributions

We anticipate that participants will report significantly higher rapport and connectedness in the identity-continuous condition. In other words, H1 and H2 are expected to be supported: continuous identity will foster smoother interactions and a deeper bond than when the agent “resets” persona each scene. For example, keeping the same name, voice and memory may help users feel an ongoing partnership, consistent with the notion that connectedness develops over repeated interactions. By contrast, in the discontinuous condition the break in identity may act like a scene change, preventing cumulative bond formation.
(From interviews, we expect that credibility (an agent’s perceived trustworthiness or competence) will be mentioned more positively under continuity.) Continuous identity may lead users to perceive the agent as more reliable and coherent, whereas discontinuity might introduce doubt (e.g., “Why is this new voice here?”). These insights will extend theoretical understanding of agent design by showing that identity design, not just visual fidelity or behavior influences social metrics. This complements existing HCI theories on trust and anthropomorphism, adding empirical evidence about persona continuity. We effectively test that a single persona transcending form enhances user–agent rapport.

Practically, the results will provide design guidelines for VR developers. If continuity proves beneficial, designers should ensure that characters retain key identity markers across different contexts or appearances. For instance, a tutorial agent that later becomes an in-game companion should keep a recognizable name and voice to leverage established rapport. Such guidelines can improve user experience in VR games, training, and social simulations. On the other hand, if discontinuity shows little effect or even benefits (e.g., novelty reduces rapport but adds intrigue), designers might instead vary agents freely. We will articulate these implications clearly: for example, “Use consistent naming and vocal cues for an agent that appears in multiple forms to maximize emotional engagement” (if supported by data).

Finally, this study’s mixed-methods approach contributes to research methodology in VR as well. By combining between-subject design, we offer a template for future multi-agent experiments. Overall, we expect to contribute both empirically and practically to the field of HCI and VR agent design.


## 6. References




