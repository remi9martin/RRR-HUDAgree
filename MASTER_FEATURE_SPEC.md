# RRR Sales HUD - MASTER FEATURE SPEC
**Source**: User's original vision transcript (Jan 5 at 1:04 AM)

---

## I. LEAD INTELLIGENCE (Pre-Call Data)
| Feature | Description |
|---------|-------------|
| **Full Background Profile** | Business info, life details, social media, photos, comments |
| **Mood History** | When they're in a good mood (from social analysis) |
| **Personality Type** | Jump-head-first vs cautious, detail-oriented, etc. |
| **Interests** | Cat lover? Motorcycles? Labrador named Frankie? |
| **Life Events** | "Family member died, no health insurance" - sensitive context |
| **Education/Income** | Estimated levels from public data |
| **Previous Call History** | What was said before, callbacks, questions asked |

---

## II. LIVE CALL METRICS
| Metric | What It Tracks |
|--------|----------------|
| **Time on Call** | Total duration |
| **Time Since Lead Spoke** | Silence timer - "30 seconds since they spoke" |
| **Tangent Timer** | "How long has your current tangent been going?" |
| **Dominance Split** | Who's talking more (Agent vs Lead %) |
| **Questions Asked by Lead** | Count + bullet points of what they asked about |
| **Interest Signals** | Moments where they said "that sounds interesting" |
| **Dislike Signals** | Moments they went quiet or negative |
| **Confidence Interval** | "70% likely to close" → updates live |
| **Attention Probability** | "70% chance not paying attention" |

---

## III. AGENT RATING (Self-Improvement)
| Metric | What It Tracks |
|--------|----------------|
| **Following Playbook** | Is agent sticking to script? |
| **Delivery Quality** | Interesting vs boring |
| **Repetition Alert** | "You're repeating yourself" |
| **Pace Check** | Speaking too fast/slow |
| **Speaking in Circles** | Rambling detection |
| **Improvement Suggestions** | "Engage with client more", "Ask if they're following" |

---

## IV. SUGGESTED ACTIONS (Prompts)
| Action Type | Example |
|-------------|---------|
| **Leading Questions** | Probe personal life, seem innocent but gather data |
| **Retention Checks** | "Am I boring you?", "Going too fast?", "You're a smart guy" |
| **Attention Snaps** | "Pretend cough, then 'are you still there?'" |
| **Callback Hooks** | "Ask about their pet" when time is right |
| **Startling Statement** | When attention is dropping, say something unexpected |
| **Joke Insert** | System notices good moment for witty comment |
| **Frankie Moment** | "Good time to bring up YOUR dog Frankie" (agent's rapport tool) |

---

## V. EMOTIONAL INTELLIGENCE
| Feature | Description |
|---------|-------------|
| **Emotion Speedometer** | Not just "angry" but HOW angry (needle gauge) |
| **Sentiment Direction** | Leaning towards anger vs calm |
| **Stimulation Level** | Overstimulated / understimulated / tired / happy |
| **Manipulation Detection** | Are THEY trying to manipulate the agent? |
| **Pattern Matching** | "They hit 10 of the bullet points for angry" |

---

## VI. PSYCHOLOGY FRAMEWORK
| Framework | Implementation |
|-----------|----------------|
| **PBD Life Position Scale** | Survival → Security → Success → Significance |
| **Chase Hughes Techniques** | Agreeableness, intention detection, seed planting |
| **Persuasion Science** | Cite studies on in-person vs phone effectiveness |

---

## VII. AGENT PROFILE (Match Engine)
| Feature | Description |
|---------|-------------|
| **Agent Interests** | What YOU can speak passionately about |
| **Agent Social Profile** | Your background for genuine rapport |
| **Shared Interest Finder** | "You both have Labradors" → prompt to use |
| **Comfort Level Setting** | Experience level affects suggestions |

---

## VIII. VISUAL CONSIDERATIONS
| Question | To Research |
|----------|-------------|
| **Face on Screen** | Does seeing lead's face help agent perform? |
| **AI Pretty Face** | Would a generated pleasant face help? |
| **Blank Silhouette** | Or is no face better? |

---

## IX. REMI MODE (Training/Learning)
| Feature | Description |
|---------|-------------|
| **Source Attribution** | Every prompt shows its source technique |
| **Format** | "[Chase Hughes - Priming] Say: 'Most successful companies...'" |
| **Use Case** | Reviewing recordings, learning what was applied where |
| **Toggle** | Switch between Agent Mode (clean) and Remi Mode (annotated) |

### Example Remi Mode Output:
```
💡 [Chase Hughes - Statements > Questions] 
   Say: "Tell me about your budget timeline."

⚠️ [Hawkins Level 150 - Anger Detected]
   Action: "Validate their position. Don't argue."

🐕 [Rapport Match - Shared Interest]
   Say: "I've got a Labrador too - Frankie. They're the best."
```
