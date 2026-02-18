# GTC 2026 Schedule & Game Plan Assistant - Skill Package

## 📋 Overview

This is a complete Claude Skill designed to help attendees of **NVIDIA GTC 2026** (San Jose, March 15-19) create personalized conference schedules and strategic game plans.

The skill intelligently maps user interests and goals to conference topics, then generates detailed day-by-day itineraries with session recommendations, networking strategies, and logistical tips.

---

## 📦 Package Contents

### 1. **gtc-2026-scheduler-skill.md** (Main Skill File)
The core skill definition that Claude uses to generate personalized game plans.

**What it covers:**
- Interest discovery and mapping (15+ topic areas)
- Multi-day schedule building (March 15-19)
- Audience level personalization (beginner/intermediate/expert)
- Goal-based recommendations (learning, networking, recruitment, investment, etc.)
- Conflict resolution and backup suggestions
- Networking and logistics strategies
- Example use cases for different personas

**Key sections:**
- Core competencies
- Workflow (interest discovery → constraints → schedule building → recommendations)
- GTC 2026 conference topics and tracks
- Output formats
- Success metrics

### 2. **gtc-2026-evals.json** (Evaluation Suite)
Comprehensive evaluation test cases for validating skill performance.

**Includes 5 distinct evaluation scenarios:**

1. **AI Engineer Learning GenAI** - Intermediate engineer wanting production techniques
2. **Executive Scouting Opportunities** - VC with 2-3 days, looking for trends/investments
3. **Student Exploring ML & Robotics** - Beginner student, 5 days, seeking mentorship
4. **Conflict Resolution** - Testing overlap handling and prioritization
5. **Hardware-Focused Engineer** - Expert wanting deep GPU/systems knowledge

**Each eval includes:**
- Specific user persona and constraints
- Expected output characteristics
- Success criteria (7-10 per eval)
- Testing guidance

### 3. **gtc-2026-implementation-guide.md** (Usage Guide)
Practical, example-driven guide showing how to use the skill.

**Features:**
- Quick start instructions (4-step activation)
- 3 detailed real-world examples with full output:
  - Data scientist (3 days, RAG focus)
  - Executive/VC (1.5 days, networking focus)
  - Student (5 days, mentorship focus)
- Customization features and special requests
- Tips for before/during/after conference
- Troubleshooting guide
- Resource links

**Each example shows:**
- Full user input
- Complete personalized game plan (day-by-day)
- Networking strategy
- Logistics and pro tips
- Follow-up action plan

### 4. **This README.md** (You're reading it!)
Overview, quick start, and file guide.

---

## 🚀 Quick Start

### Installation (Option A: Upload to Claude.ai)

1. Open Claude.ai chat
2. Click the paperclip or file upload icon
3. Upload all `.md` and `.json` files from this package
4. Say: _"Using these skill files, help me create a personalized GTC 2026 schedule"_

### Installation (Option B: Integrated Skill)

If you're integrating this into a system that supports Claude Skills:

1. Copy `gtc-2026-scheduler-skill.md` to your skills directory
2. Reference it in your Claude configuration
3. Users can invoke: _"Use the GTC 2026 Scheduler skill..."_

### First Use

**Tell Claude:**
```
I'm attending NVIDIA GTC 2026 and need help planning my schedule. 
I'm a [your role] interested in [your topics].
I have [your availability] and my goal is to [your goal].
```

**Claude will:**
1. Ask clarifying questions about your interests and goals
2. Gather constraints (availability, preferences, logistics)
3. Generate a detailed day-by-day game plan
4. Provide session recommendations with rationale
5. Suggest networking opportunities and strategies

**You'll receive:**
- Day-by-day schedule with times
- Specific session recommendations by topic
- Backup/alternative options
- Networking and logistics tips
- What to pack and resources to review

---

## 💡 What This Skill Does

✅ **Understands Your Goals**
- Learning & skill development
- Networking & connections
- Recruitment / talent scouting
- Investment opportunities
- Career exploration
- Technical deep dives

✅ **Maps to Conference Content**
- 13+ major topic tracks
- 3 experience levels (beginner/intermediate/expert)
- 5 days of sessions and events
- Mix of keynotes, sessions, workshops, networking

✅ **Creates Realistic Schedules**
- 4-6 sessions per day (realistic for retention)
- Balances learning with networking
- Accounts for travel time between sessions
- Includes breaks and meal times
- Respects availability constraints

✅ **Handles Complexity**
- Overlapping sessions with priority logic
- Limited availability (2-3 days vs. full 5)
- Role-specific recommendations
- Budget considerations
- Networking vs. learning trade-offs

✅ **Provides Strategic Context**
- Why each session matters
- What to expect at keynotes
- Networking event strategies
- Booth visit priorities
- Pro tips and logistics

---

## 👥 Example Personas Covered

The skill handles diverse attendee types:

1. **AI/ML Engineers** - Focused learning on specific technologies
2. **Researchers** - Deep technical exploration, expert-level content
3. **Executives** - Trend spotting, strategic overview, networking
4. **Investors/VCs** - Opportunity scouting, founder meetings
5. **Students** - Career exploration, mentorship, hands-on learning
6. **Hardware Specialists** - GPU/system optimization, architecture
7. **Product Managers** - Market trends, feature planning
8. **Sales/Business Dev** - Partnership opportunities, customer insights
9. **Startup Founders** - Inspiration, partnerships, funding insights
10. **HR/Recruiting** - Talent scouting, team building

---

## 📊 Skill Quality Metrics

**Testing Approach:**
- 5 comprehensive evaluation scenarios
- Success criteria per scenario (7-10 checks each)
- Coverage of simple and complex use cases
- Edge case handling (conflicts, constraints)
- Different persona types and goals

**Expected Performance:**
- 80%+ success criteria met per evaluation
- Consistent, personalized recommendations
- Clear rationale for all suggestions
- Realistic schedule constraints honored
- Practical, actionable output

**Human Review:**
- Each evaluation includes specific success criteria
- Can be graded manually or with automated checkers
- Evidence-based (transcript, outputs, metrics)

---

## 🎯 Conference Context

**Event:** NVIDIA GTC 2026
**Location:** San Jose, California
**Dates:** 
- Workshops: March 15
- Keynote: March 16
- Main Conference: March 16-19

**Conference Tracks:**
- AI Platforms & Deployment
- Generative AI & Content Creation  
- Agentic AI
- Conversational AI
- Data Center & Cloud Infrastructure
- Computer Vision & Video Analytics
- AR/VR/Spatial Computing
- Cybersecurity
- Robotics & Autonomous Systems
- Healthcare & Life Sciences
- Enterprise & Industry Applications
- Hardware & GPU Architecture
- Developer Tools & Frameworks

**Session Format:**
- Keynotes (large, no registration needed)
- Technical sessions (up to 1 hour)
- Boot camps & workshops (hands-on, full day)
- Expert connect panels (Q&A with speakers)
- Vendor booths (product demos)
- Networking events (receptions, mixers)
- Career fair (for students)

---

## 📖 How to Use Each File

### For Conference Attendees
1. Start with **gtc-2026-implementation-guide.md**
   - See if your persona matches any examples
   - Understand the process
   - Get inspired by detailed sample plans

2. Use **gtc-2026-scheduler-skill.md** (via Claude)
   - Upload the skill file
   - Answer interest discovery questions
   - Receive your personalized game plan

### For Skill Developers/Evaluators
1. Review **gtc-2026-scheduler-skill.md**
   - Understand skill architecture
   - Review competencies and workflow
   - Check success metrics

2. Study **gtc-2026-evals.json**
   - Understand test scenarios
   - Review success criteria
   - Plan evaluation approach

3. Reference **gtc-2026-implementation-guide.md**
   - See real-world outputs
   - Understand expected quality
   - Identify edge cases

### For Integration/Customization
1. Adapt **gtc-2026-scheduler-skill.md**
   - Customize topic areas for future events
   - Add new evaluation criteria
   - Extend for other NVIDIA events or conferences

2. Update **gtc-2026-evals.json**
   - Add more personas
   - Test new scenarios
   - Track improvements

---

## 🔧 Customization & Extension

### Adapt for Other Conferences
- Replace topic areas with conference-specific tracks
- Update dates and venue information
- Modify audience levels as needed
- Adjust networking opportunities

### Enhance the Skill
- Add real-time session availability checking
- Integrate with registration systems
- Add post-event follow-up planning
- Include travel/accommodation suggestions
- Expand to multi-track recommendations

### Create New Evaluations
- Add niche personas (e.g., "Sustainability Focus")
- Test edge cases (large groups, specific constraints)
- Validate for different experience levels
- Test with real attendees post-conference

---

## 📋 Checklist: Before Using the Skill

- [ ] Have at least 3-5 specific interests or topics in mind
- [ ] Know your experience level (beginner/intermediate/expert)
- [ ] Know your availability (how many days you can attend)
- [ ] Identify your primary goal (learning/networking/scouting/etc.)
- [ ] Gather any constraints (flights, meetings, budget limits)
- [ ] Have notebook/device ready to capture recommendations
- [ ] Plan to verify session details on official GTC website

---

## ❓ FAQ

**Q: Is the skill specific to GTC 2026 only?**
A: Yes, it's calibrated for March 2026. You could adapt it for future years or other conferences.

**Q: Can it access the live session catalog?**
A: The catalog requires JavaScript rendering. The skill recommends sessions by topic and guides you to search the live catalog.

**Q: What if a session fills up while I'm traveling?**
A: That's why the skill provides backup options and alternatives for every recommendation.

**Q: Can I change my schedule mid-conference?**
A: Absolutely! The plan is a guide. Flexibility and serendipity are part of the conference experience.

**Q: Does the skill help with networking strategy?**
A: Yes! It includes specific recommendations for networking events, booth visits, expert sessions, and unstructured time.

**Q: What if I'm attending for 1 day only?**
A: The skill adapts. Just specify your single day and goal (keynote, networking, one track deep-dive).

**Q: Can I share my game plan with my team?**
A: Yes! The output is designed to be printable, shareable, and discussion-friendly.

---

## 🤝 Feedback & Improvement

### Report Issues
- Session recommendations seem off?
- Schedule conflicts not resolved?
- Missing important topics?
- Persona not well-served?

### Suggest Improvements
- New persona types to cover
- Better output formats
- Additional strategic considerations
- Integration with other tools

---

## 📚 Additional Resources

**NVIDIA GTC 2026 Official Resources:**
- GTC Homepage: https://www.nvidia.com/gtc/
- Session Catalog: https://www.nvidia.com/gtc/session-catalog/
- Conference Topics: https://www.nvidia.com/gtc/conference-topics/
- Training & Workshops: https://www.nvidia.com/gtc/training/
- Travel & Venue: https://www.nvidia.com/gtc/travel-and-venue/
- FAQ: https://www.nvidia.com/gtc/faq/

**File Structure:**
```
gtc-2026-scheduler-skill-package/
├── README.md                              (This file)
├── gtc-2026-scheduler-skill.md            (Main skill)
├── gtc-2026-evals.json                    (Test scenarios)
└── gtc-2026-implementation-guide.md       (Usage examples)
```

---

## 🎓 Learning Path

1. **Understand** (5 min) - Read this README
2. **Explore** (15 min) - Skim the implementation guide examples
3. **Learn** (10 min) - Review the main skill file structure
4. **Evaluate** (20 min) - Study evaluation scenarios
5. **Practice** (30 min) - Create your own game plan with Claude
6. **Adapt** (variable) - Customize for your needs

**Total Time to Mastery:** ~1.5 hours

---

## ✨ What Makes This Skill Effective

1. **Personalization** - Adapts to role, goal, experience level, availability
2. **Context-Aware** - Understands conference structure and logistics
3. **Practical** - Provides actionable, realistic schedules
4. **Strategic** - Balances multiple priorities (learning, networking, rest)
5. **Flexible** - Handles constraints and provides alternatives
6. **Well-Tested** - Includes comprehensive evaluation suite
7. **Well-Documented** - Clear examples and usage guide

---

## 🚀 Let's Get Started!

Ready to maximize your GTC 2026 experience?

1. **Upload the skill files to Claude**
2. **Tell Claude:** _"Help me create a personalized GTC 2026 schedule. I'm a [role] interested in [topics], available [dates], and my goal is [goal]."_
3. **Answer the discovery questions** (2-3 minutes)
4. **Receive your game plan** (detailed, day-by-day)
5. **Adjust as needed** and print/save for the conference

---

**Enjoy GTC 2026! 🎉**

*Questions about this skill? Check the implementation guide or evaluation scenarios for more examples.*
