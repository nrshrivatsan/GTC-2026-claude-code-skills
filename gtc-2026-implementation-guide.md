# GTC 2026 Scheduler Skill - Implementation Guide

## Quick Start

### How to Use This Skill

This skill generates personalized conference schedules and strategic game plans for NVIDIA GTC 2026.

#### Step 1: Prepare the Skill
1. Save `gtc-2026-scheduler-skill.md` to your skills directory
2. Include it in your Claude configuration or upload it when starting a conversation

#### Step 2: Activate the Skill
Tell Claude: 
> "Using the GTC 2026 scheduler skill, help me create a personalized game plan for the conference."

#### Step 3: Answer Discovery Questions
The skill will ask you about:
- Your role/background
- Primary and secondary interests
- Experience level (beginner/intermediate/expert)
- Your main goal(s) for attending
- Time availability
- Preferences (pace, networking, etc.)

#### Step 4: Receive Your Game Plan
You'll get a detailed, personalized itinerary including:
- Day-by-day schedule
- Recommended sessions (with rationale)
- Networking opportunities
- Backup options
- Pro tips and logistics

---

## Integration Examples

### Example 1: Basic Usage

**User Input:**
```
I'm a data scientist interested in learning about RAG and LLMs. 
I have 3 days (March 16-18) and I'm intermediate level.
I want a good balance of learning and networking.
```

**Skill Output:**

```
🎯 YOUR GTC 2026 GAME PLAN
═════════════════════════════════════════

PROFILE:
• Role: Data Scientist
• Interests: RAG, LLMs, GenAI
• Level: Intermediate
• Availability: 3 days (March 16-18)
• Goal: Learning + Networking balance

SUMMARY:
You'll focus on Generative AI track with deep dives into RAG and LLM 
production patterns. Light networking integrated into breaks and meals.

═════════════════════════════════════════

MARCH 16 (Monday)
─────────────────
Theme: Keynotes & Foundation Setting

9:00am   | Opening Keynote                    | Must-Attend | Why: Major announcements
         | (Arrive early - expect crowds)    |             |

10:30am  | Coffee & Networking (Hall)         | Networking  | Get oriented, meet people

11:00am  | "Building Production LLMs"         | Generative  | Core interest - understand
         | (Level: Intermediate)             | AI          | production requirements

12:30pm  | Lunch (Sponsor area - look        | Networking  | Free lunch + connections
         | for Databricks/OpenAI booths)      |             |

2:00pm   | "Advanced RAG Architectures"      | Generative  | Primary focus
         | (Level: Intermediate)             | AI          |

3:30pm   | Break & Booth Exploration         | Demo        | See vector DB & LLM tools
         | Recommended: Vector Store booths  |             |

5:00pm   | Reception (Networking)            | Social      | Unwind, meet other learners

NOTES FOR TODAY:
• Keynote is mandatory but will be crowded - plan to arrive 15 min early
• Bring notebook for keynote insights
• March 16 is busy but sets context for everything else
• Location tip: Lunch is near main hallway - good for people-watching

BACKUP SESSIONS (if your preferred ones fill up):
• "LLM Fine-Tuning Best Practices" - Similar level, complementary topic
• "Deploying LLMs in Production" - Practical applications focus

═════════════════════════════════════════

MARCH 17 (Tuesday)
─────────────────
Theme: Deep Dives on RAG & Optimization

9:00am   | Boot Camp: "RAG in Depth"         | Training    | Hands-on - critical for 
         | (March 15 makeup, if available)   | Labs        | understanding internals

11:00am  | "Prompt Engineering for RAG"      | Generative  | Tactical skills to implement
         | (Level: Intermediate)             | AI          |

12:30pm  | Lunch & Networking                | Social      | Sit with people from previous
         | (Use this to find people from     |             | sessions
         | morning sessions)                  |             |

2:00pm   | "Evaluating RAG Systems"         | Generative  | Quality metrics - important
         | (Level: Intermediate)             | AI          | for production

3:30pm   | Expert Connect: RAG Panel        | Networking  | Q&A with researchers
         | OR "Vector Databases at Scale"    |             | 

5:00pm   | Free time / Booth visits         | Demo        | Explore Pinecone, Weaviate,
         |                                   |             | Milvus booths

NOTES FOR TODAY:
• Slightly lighter schedule allows for exploration
• "Expert Connect" sessions are gold - come with 2-3 questions
• Use booth time to understand production tools

═════════════════════════════════════════

MARCH 18 (Wednesday)
─────────────────
Theme: Production Patterns & Enterprise Scale

9:00am   | "LLM Inference at Scale"         | Generative  | Bridges to systems thinking
         | (Level: Intermediate)             | AI          |

10:30am  | "NVIDIA TensorRT for LLMs"       | Hardware    | Optimization techniques
         | (Level: Intermediate/Expert)      |             |

12:00pm  | Lunch (last day - aim for good   | Social      | Exchange contacts, plan
         | conversation)                     |             | follow-ups

1:30pm   | Choose 1:                         | Generative  | Final session - your choice
         | A) "Agentic AI Applications"      | AI / Agents | based on interests
         | B) "Monitoring LLM Systems"       |             |
         | C) "Implementing RAG in Your Org" |             |

3:00pm   | Wrap-up & Booth Returns          | Demo        | Any booths you want to revisit
         | (Take business cards & pamphlets) |             |

4:00pm   | Optional: Closing Reception      | Social      | Say goodbye, exchange info

NOTES FOR TODAY:
• Last day - prioritize any must-see sessions
• Get contact info from people you've connected with
• Take photos of booth materials for later

═════════════════════════════════════════

NETWORKING SUMMARY:
✓ Day 1: Keynote crowd, lunch networking, reception
✓ Day 2: Boot camp peers, lunch group, expert panel
✓ Day 3: Casual booth conversations, closing reception

You should meet 15-20 peers across these 3 days.

═════════════════════════════════════════

WHAT TO PACK:
□ Business cards (bring 50+)
□ Notebook & pen
□ Phone charger
□ Comfortable shoes
□ Water bottle (refill stations everywhere)

ADDITIONAL RESOURCES:
• Download GTC app for schedule updates
• Join #gtc2026 communities online
• Post-conference: YouTube will have session recordings

NEXT STEPS:
1. Go to https://www.nvidia.com/gtc/session-catalog/
2. Search for sessions by topic and time
3. Create your personal GTC account and save these sessions
4. Print or screenshot this plan
5. Feel free to deviate - this is a guide, not law!
```

---

### Example 2: Executive/VC Focus

**User Input:**
```
I'm a VC looking at AI investment opportunities. 
I only have March 16 afternoon + March 17 morning (1.5 days).
I'm more beginner level - need executive briefings, not deep technical.
Maximize networking with founders and other investors.
```

**Skill Output:**

```
🎯 EXECUTIVE GAME PLAN: GTC 2026 (1.5 Days)
═════════════════════════════════════════════

PROFILE:
• Role: Venture Capitalist
• Goal: Identify investment opportunities in AI/Agents
• Time: 1.5 days (March 16 afternoon + March 17 morning)
• Level: Beginner (need executive summaries, not code)
• Networking: High priority

STRATEGY:
Focus on keynotes, enterprise applications, and VC/startup sessions. 
Leave 70% of time unstructured for meetings and networking.

═════════════════════════════════════════

MARCH 16 (Monday afternoon)
───────────────────────────
1:00pm   | Arrive & Register                 | Logistics   | Get badge, app, schedule

1:30pm   | "Agentic AI: The Next Frontier"  | Keynote     | Executive overview of 
         | (Part of morning keynote)         | Highlight   | AI trends for 2026

2:30pm   | Executive Briefing Track         | Briefing    | Curated insights for
         | (General session)                 |             | decision-makers

3:30pm   | VCs & Angels Networking Session  | Networking  | Meet other investors
         | (Look for event signage)          |             |

4:30pm   | NVIDIA Partners Roundtable       | Networking  | Understand NVIDIA strategy
         | (Registration table)              |             | & partnership opps

6:00pm   | Founders Mixer (Startup area)    | Networking  | Meet early-stage AI cos
         |                                   |             |

NOTES:
• Focus: Meet other investors, understand trends, identify startups to follow up
• Logistics: Keynote will be live-streamed/recorded if you miss part
• Pro tip: Sponsor receptions often have better VC density - ask at info desk

═════════════════════════════════════════

MARCH 17 (Tuesday morning)
──────────────────────────
9:00am   | Startup Showcase Track          | Focus       | 5-min pitches from AI
         | (if available)                  | Session     | startups

10:00am  | "Enterprise AI ROI"              | Topic       | Business case studies
         | (Level: Beginner/Executive)      | Session     |

11:00am  | Final Networking & Booth Visits | Unstructured| Visit booths: 
         |                                 | Time        | - AI infrastructure
         |                                 |             | - LLM platforms
         |                                 |             | - Enterprise software

12:00pm  | Wrap-up, exchange contacts      | -           | -

═════════════════════════════════════════

INVESTMENT FOCUS AREAS (TO EXPLORE):
☐ Agentic AI platforms (agents, orchestration, tooling)
☐ Enterprise applications (customer service, document processing)
☐ Infrastructure improvements (vector DBs, LLM inference, data pipelines)
☐ Vertical-specific AI (healthcare, finance, manufacturing)
☐ Safety & evaluation tools (monitoring, testing, compliance)

KEY BOOTHS:
Visit: NVIDIA (roadmap insight), major LLM providers, startups in above areas

NETWORKING TARGETS:
✓ 10-15 other investors
✓ 5-10 AI startup founders
✓ 2-3 NVIDIA executives or partners

═════════════════════════════════════════

LOGISTICS:
• Hotel nearby? Schedule that morning meeting for 7am, come to GTC 9am
• Keep afternoon flexible for coffee meetings with interesting founders
• Collect business cards aggressively - follow up within 48 hours
• Take photos of startup pitches/demos

FOLLOW-UP PLAN:
Within 48 hours: Reach out to 3-5 most interesting contacts
Within 1 week: Review all captured info, identify follow-up companies
Within 2 weeks: Schedule calls with top 3-5 opportunities
```

---

### Example 3: Student with Limited Experience

**User Input:**
```
I'm a grad student in ML, pretty new to the field. 
I want to explore robotics and ML careers.
I have all 5 days available.
I want hands-on learning and mentorship.
Limited budget - looking for free workshops if possible.
```

**Skill Output:**

```
🎯 STUDENT GAME PLAN: GTC 2026 (Full 5 Days)
═════════════════════════════════════════════

PROFILE:
• Role: Grad Student (Beginner to Intermediate ML knowledge)
• Interests: Robotics, Machine Learning, Career Exploration
• Availability: Full 5 days (March 15-19)
• Budget: Limited - focus on included/free activities
• Goal: Learn, find mentors, explore career paths

STRATEGY:
Boot camps (hands-on, intensive), beginner sessions with survey breadth,
heavy "Expert Connect" time, and internship/career fair activities.

═════════════════════════════════════════

MARCH 15 (Sunday) - WORKSHOP DAY
─────────────────────────────────
Pick 2 boot camps (full day each, or split):

MORNING (9am-12pm):
□ "Deep Learning Fundamentals" 
  (If you need refresher - optional)
  Why: Free, hands-on, covers backprop to transformers

AFTERNOON (1pm-5pm):
□ "Robotics with AI: Hands-On Lab"
  (Highly recommended!)
  Why: Direct robotics experience, NVIDIA robotics team leads it
  
EVENING:
Explore conference center, plan your week, relax

NOTES:
• Workshops on March 15 are FREE for registered attendees
• Get there early - popular workshops fill up
• Bring laptop if they do coding workshops

═════════════════════════════════════════

MARCH 16 (Monday) - INSPIRATION DAY
───────────────────────────────────
9:00am   | Opening Keynote                  | Must-See    | Vision-setting,
         |                                  |             | understand future of AI/robotics

10:30am  | Grab breakfast near keynote area | Casual      | Meet other students

11:00am  | "Machine Learning 101"           | Beginner    | Refresh fundamentals
         | (Level: Beginner)                | Session     |

12:30pm  | Lunch (find student groups)      | Networking  | Look for "Student Lounge"
         |                                  |             | or student organizers

2:00pm   | "Robotics with AI"               | Topic       | Your passion area
         | (Level: Beginner to Intermediate)| Session     |

3:30pm   | Booth Exploration (Robotics)    | Hands-on    | See NVIDIA Isaac, robotics
         |                                  |             | demos, meet engineers

5:00pm   | Career Panel: "Paths in AI"     | Career      | Hear from 5+ AI professionals
         |                                  | Track       | about career options

6:30pm   | Student Networking Reception    | Social      | Usually sponsored - look for it!

NOTES:
• Keynote is most crowded - arrive 30 min early
• Booth demo engineers love talking to students - ask questions!
• Student receptions often have free food

═════════════════════════════════════════

MARCH 17 (Tuesday) - LEARNING DAY 1
──────────────────────────────────
9:00am   | "Computer Vision Fundamentals"   | Beginner    | Foundational CV knowledge
         | (Level: Beginner to Intermediate)|             |

11:00am  | Expert Connect: Robotics Q&A     | Mentorship  | 1-on-1 with robotics expert
         |                                  |             | (Ask about: research, career paths)

12:30pm  | Lunch with others from 9am       | Networking  | Make friends in cohort
         | session                          |             |

2:00pm   | "Machine Learning Infrastructure"| Beginner to | Learn MLOps basics
         | (Level: Beginner to Intermediate)| Intermediate|

3:30pm   | NVIDIA Booth Deep Dive           | Hands-on    | Talk to engineers:
         |                                  |             | - ML frameworks
         |                                  |             | - CUDA basics (if interested)
         |                                  |             | - Research opportunities

5:00pm   | Free time / Explore exhibits    | Casual      |

NOTES:
• Expert Connect sessions are gold - bring a list of 3-5 questions
• Engineers at booths often know about internships - ask!
• Many companies sponsor free student badges for career fair

═════════════════════════════════════════

MARCH 18 (Wednesday) - LEARNING DAY 2
──────────────────────────────────────
9:00am   | "Neural Networks in Robotics"    | Intermediate| Combine interests
         | (Level: Intermediate)            |             |

10:30am  | "Getting Started with CUDA"      | Beginner    | Learn GPU computing
         | (Optional - if interested)       |             |

12:00pm  | Lunch networking                 | Social      | Meet people from today's
         |                                  |             | sessions

1:30pm   | Student Career Fair / Job       | Career      | Companies hiring interns
         | Fair (if available)              | Track       | and entry-level roles
         | OR                               |             |
         | "Research Opportunities in AI"   |             | Or track academic path
         | Panel                            |             |

3:00pm   | "Practical ML Project Walkthrough"| Beginner to | Learn from real projects
         | (Level: Intermediate)            | Intermediate|

4:30pm   | Free exploration / rest         | Casual      | You've learned a lot!

5:00pm   | Optional: Startup Showcase      | Optional    | See what students/young
         | (If available)                   |             | founders are building

NOTES:
• Career fair is incredibly valuable - bring extra resumes
• Ask career fair companies about internships/grad roles
• Day 3 can feel overwhelming - take breaks as needed

═════════════════════════════════════════

MARCH 19 (Thursday) - SYNTHESIS DAY
───────────────────────────────────
9:00am   | Pick 2 sessions you want to     | Focus       | Fill in gaps from earlier
         | revisit (or new ones)            | Sessions    |

11:00am  | Booth returns                    | Logistics   | Get business cards, pamphlets
         |                                  |             | from companies of interest

12:30pm  | Final lunch & wrap-up           | Reflection  | Journal/note what you learned

2:00pm   | Closing session (if available)  | Optional    |

NOTES:
• Don't overcommit Thursday - you'll be tired
• Spend time reflecting on what you learned
• Get contact info from mentors/interesting people

═════════════════════════════════════════

MENTORSHIP STRATEGY:
Day 1: Keynote (see the vision)
Day 2: Expert Connect robotics Q&A + booth engineers
Day 3: Career fair + research opportunities panel
Day 4: Connect with specific companies interested in you
Day 5: Exchange info with mentors, plan follow-ups

TARGET CONTACTS:
✓ 3-5 NVIDIA engineers/researchers
✓ 2-3 professionals from "Career Paths" panel
✓ Companies at career fair (collect business cards)
✓ 1-2 fellow students (stay connected for study/career)

═════════════════════════════════════════

BUDGET TIPS (How to do GTC cheaply):
☐ Register as student (often free or discounted)
☐ Workshops included with registration
☐ Sponsored lunches are free
☐ Student receptions have free food
☐ Many company booths give out free stuff
☐ Video recordings available post-event (free online later)

WHAT TO BRING:
□ 50+ resumes (for career fair!)
□ Notebook & pen
□ Business cards (get some printed cheaply)
□ Laptop (for any hands-on labs)
□ Comfortable shoes (you'll walk a lot!)
□ Confidence - everyone loves enthusiastic students!

DELIVERABLES TO TAKE HOME:
✓ Business cards from 10+ professionals
✓ Contact info from 2-3 potential mentors  
✓ Notes from all sessions (review recordings later)
✓ Insights into robotics/AI careers
✓ Potential internship leads
✓ A plan for next 3-6 months of learning

FOLLOW-UP ACTION PLAN:
Within 48 hours:
- Email mentors thanking them, ask for coffee chat
- Follow up with career fair companies
- Take notes from videos you want to review

Within 1 week:
- Schedule calls with top companies
- Review session recordings you missed
- Plan next learning steps

Within 1 month:
- Complete any projects inspired by GTC
- Apply to internships you discovered
- Stay in touch with peers you met
```

---

## Customization Features

### Adjust the Plan

After receiving your initial game plan, you can request:

- **"Add more networking time"** - Less sessions, more unstructured time
- **"Make it more intensive"** - More sessions, fewer breaks
- **"Focus on [specific topic]"** - Shift balance to favorite area
- **"I can only do [2] days now"** - Regenerate for shorter availability
- **"Change the pace"** - Beginner → Intermediate, or vice versa
- **"What if I miss morning sessions?"** - Afternoon-focused alternative
- **"Add expert talks"** - More advanced sessions mixed in

### Special Requests

- *"I know John from [Company] - add times to meet him"*
- *"I want startup-focused recommendations"*
- *"Minimize travel between sessions"*
- *"I want to see all hardware announcements"*
- *"Create an evening networking plan"*

---

## Tips for Success

### Before the Conference

✓ Register early (popular sessions fill up)
✓ Create a GTC account and bookmark your sessions
✓ Download the GTC app for real-time updates
✓ Print your game plan or save to your phone
✓ Join online GTC communities (#gtc2026, subreddits, Discord)
✓ Review speaker bios if interested in specific talks
✓ Plan your accommodation near the venue

### During the Conference

✓ Arrive early for popular keynotes/sessions
✓ Be flexible - best sessions often have lines
✓ Talk to people in your sessions (you'll make friends)
✓ Collect business cards (ask for them!)
✓ Charge your phone constantly
✓ Hydrate (San Jose in March can be hot)
✓ Take photos of slides/booths for later review
✓ Don't skip meals - energy management matters

### After the Conference

✓ Follow up with contacts within 48 hours
✓ Review session recordings (usually available within weeks)
✓ Share notes with your team/colleagues
✓ Implement what you learned
✓ Stay in touch with peers you met
✓ Write a conference summary for your organization

---

## Troubleshooting

**Q: The schedule feels too packed. What do I do?**
A: Reduce your target sessions (4-5/day instead of 6). Quality > quantity. Use your extra time to network and explore.

**Q: I want to attend [Session A] AND [Session B] but they overlap.**
A: Choose the higher-priority one, watch the other on-demand later. Sessions are recorded.

**Q: I don't know what sessions are best for me.**
A: Start by going to the conference topics page, browse a few session titles, then adjust your game plan with more specific feedback.

**Q: I'm overwhelmed. What are the must-sees?**
A: 
1. Opening Keynote (March 16)
2. 2-3 sessions directly related to your main interest
3. 1-2 networking events
Everything else is bonus.

**Q: What if my plans change during the conference?**
A: That's fine! The game plan is a guide. If an amazing unexpected opportunity comes up, take it. Flexibility is part of the fun.

---

## Additional Resources

- **GTC Homepage**: https://www.nvidia.com/gtc/
- **Live Session Catalog**: https://www.nvidia.com/gtc/session-catalog/
- **Conference Topics**: https://www.nvidia.com/gtc/conference-topics/
- **Travel & Venue**: https://www.nvidia.com/gtc/travel-and-venue/
- **Speakers**: https://www.nvidia.com/gtc/speakers/
- **FAQ**: https://www.nvidia.com/gtc/faq/

---

## Feedback

Have ideas for improving this skill? Share feedback:
- What additional information would help?
- Any other personas you'd like to see?
- Better ways to present schedules?
- Missing recommendations?

---

**Enjoy GTC 2026! 🚀**
