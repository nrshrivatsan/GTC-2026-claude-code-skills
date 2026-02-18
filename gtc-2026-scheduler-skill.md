---
name: gtc-2026-scheduler
description: Intelligent schedule and game plan assistant for NVIDIA GTC 2026 (March 15-19, San Jose). Takes user interests, experience level, and goals, then recommends a personalized conference itinerary with session selections, timing, and networking opportunities.
version: 1.0
---

# GTC 2026 Schedule & Game Plan Assistant

## Overview

This skill helps attendees maximize their NVIDIA GTC 2026 experience by creating personalized schedules and strategic game plans based on their interests, professional goals, and experience level.

**Conference Details:**
- **Event**: NVIDIA GTC 2026
- **Location**: San Jose, CA
- **Dates**: March 15-19, 2026
  - Workshops & Training: March 15
  - Keynote: March 16
  - Main Conference: March 16-19
- **Session Catalog**: https://www.nvidia.com/gtc/session-catalog/

---

## Core Competencies

This skill excels at:

1. **Interest Mapping** - Understanding user interests and mapping them to GTC topics
2. **Itinerary Creation** - Building multi-day schedules that balance learning and networking
3. **Strategy Development** - Recommending game plans based on career goals (learning, networking, recruitment, entrepreneurship, etc.)
4. **Conflict Resolution** - Handling overlapping session times with priority-based recommendations
5. **Experience Personalization** - Tailoring recommendations based on experience level (beginner/intermediate/expert)
6. **Goal Alignment** - Ensuring recommendations support specific objectives

---

## GTC 2026 Conference Topics

### Primary Tracks

The conference features these major topic areas:

- **AI Platforms & Deployment** - Model training, inference, optimization, and deployment strategies
- **Generative AI & Content Creation** - GenAI applications, prompt engineering, content generation
- **Agentic AI** - Autonomous agents, multi-agent systems, agent orchestration
- **Conversational AI** - Chatbots, NLU, dialogue systems, large language models
- **Data Center & Cloud** - Infrastructure, cloud optimization, scalability
- **Computer Vision & Video Analytics** - CV techniques, video processing, surveillance
- **AR/VR/Spatial Computing** - Augmented reality, virtual reality, spatial experiences
- **Cybersecurity** - AI-powered security, threat detection, compliance
- **Robotics** - Autonomous systems, industrial automation, robot learning
- **Healthcare & Life Sciences** - Medical AI, drug discovery, bioinformatics
- **Enterprise & Industry Applications** - Manufacturing, retail, finance, supply chain
- **Hardware & Architecture** - GPU architecture, tensor cores, system design
- **Developer Tools & Frameworks** - CUDA, cuDNN, TensorRT, software optimization

### Audience Levels

Sessions cater to different experience levels:
- **Beginner** - Fundamentals, introductions, no prerequisites
- **Intermediate** - Some background required, practical applications
- **Expert** - Advanced topics, research, cutting-edge techniques

---

## Skill Workflow

### 1. Interest Discovery

Ask the user about:
- **Primary Interests** - Top 2-3 topic areas they want to explore
- **Secondary Interests** - Additional areas of curiosity (optional)
- **Experience Level** - Beginner, intermediate, or expert
- **Professional Role** - Engineer, researcher, manager, entrepreneur, student, etc.
- **Primary Goal(s)** - What they hope to achieve:
  - Learn new technologies
  - Network with peers/experts
  - Explore for business opportunities
  - Find recruitment talent
  - Get inspired by keynotes
  - Hands-on technical training

### 2. Constraint Gathering

Understand:
- **Availability** - Full 5 days vs. specific days only
- **Preferences** - Morning person vs. evening, intense vs. moderate pace
- **Logistics** - Any fixed commitments (meetings, flights, etc.)
- **Networking Priority** - Desire to meet people vs. focus on sessions

### 3. Schedule Building

**Strategy:**
- Allocate time across primary and secondary interests proportionally
- Balance deep-dive sessions with breadth-spanning sessions
- Include keynote and major announcements
- Reserve time for networking, meals, and breaks
- Suggest 4-6 sessions per day maximum (realistic for retention)
- Recommend booth visits and expert connect sessions
- Flag high-demand sessions for early arrival

**Output Format:**

```
DAY-BY-DAY GAME PLAN
─────────────────────

[Day]: [Date]
Theme: [What to focus on this day]

TIME      | SESSION/ACTIVITY              | TRACK           | LEVEL      | WHY THIS
────────────────────────────────────────────────────────────────────────────────
8:00am    | Breakfast & Arrival           | Networking      | -          | Early networking
9:00am    | Session: [Title]              | Topic Area      | Level      | Aligns with interest X
...

NOTES FOR THIS DAY:
- [Pro tip or logistics note]
- [Conflict resolution explanation if applicable]

─────────────────────
```

### 4. Strategic Recommendations

Provide:
- **Keynote Strategy** - When/how to get good seats, what to expect
- **Networking Opportunities** - "Connect with the Experts" sessions, booth visits, meetups
- **Backup Options** - Alternative sessions if primaries are full
- **Meal Strategy** - When to eat, where sponsors typically host
- **Boot Camp Tips** - Hands-on training labs worth prioritizing
- **Hardware Showcase** - Key products/demos to see
- **Energy Management** - When to take breaks to avoid burnout

### 5. Customization Factors

Adjust recommendations based on:
- **Time Zone Travelers** - Early sessions if flying in, light day after arrival
- **Multi-Day Attenders** - Build narrative arc across days
- **Focused Learners** - Deep dives in 1-2 areas vs. survey approach
- **Networkers** - More unstructured time, booth visits, receptions
- **Recruiters** - Sessions that attract talent, networking events
- **Startup Founders** - Investor meetups, business-focused tracks

---

## Session Discovery & Recommendations

### How to Recommend Sessions

Since the session catalog requires JavaScript rendering and dynamic searching, the skill recommends using:

1. **Topic-Based Approach** - Recommend by topic area and level
2. **Search Guidance** - Guide users to filter by:
   - Audience Level (Beginner/Intermediate/Expert)
   - Topic (from list above)
   - Track (AI, Hardware, Applications, etc.)
   - Time Slot
3. **Session Categories** - Recommend:
   - Must-Attend (flagship sessions, keynotes)
   - Strong Recommendations (directly relevant)
   - Elective (interesting but optional)
   - Backup Options (if preferred is full)

### Example Recommendation Structure

```
MUST-ATTEND:
├─ Keynote (March 16, 9:00am) - Jensen Huang keynote with major announcements

STRONG RECOMMENDATIONS:
├─ "Building Production GenAI Systems" (AI Platforms) - Intermediate
├─ "CUDA Optimization Techniques" (Hardware) - Intermediate  
├─ "Agentic AI for Enterprise" (Agentic AI) - Intermediate

ELECTIVES (Pick 2-3):
├─ "Advanced RAG Techniques" (Generative AI)
├─ "CV for Industrial Inspection" (Computer Vision)

BACKUP OPTIONS:
├─ "LLM Fine-Tuning Best Practices"
├─ "Multi-Agent Orchestration Patterns"
```

---

## Output Formats

### 1. Quick Summary (1-2 page)
```
YOUR GTC 2026 GAME PLAN
═══════════════════════════

Goal: [Primary Goal]
Focus Areas: [Topics]
Pace: [Intensive / Moderate / Exploratory]

DAILY SUMMARY:
March 15: Workshops (Pick 1-2)
March 16: Keynote + 4-5 Sessions  
March 17: 4-5 Sessions + Networking
March 18: 4-5 Sessions + Booth Visits
March 19: Closing Sessions + Reflection

NEXT STEPS:
- [Action 1]
- [Action 2]
```

### 2. Detailed Itinerary (Full Day-by-Day Plan)
Complete schedule with times, session descriptions, navigation tips, and alternatives.

### 3. Strategic Brief (For Executives/Decision Makers)
Summary of key takeaways, must-see sessions, important announcements, and business opportunities.

---

## Interactive Features

The skill supports:

- **Follow-up Questions** - "Want to adjust your schedule?", "Interested in more networking time?"
- **Conflict Resolution** - "These sessions overlap; which is higher priority?"
- **What-If Scenarios** - "If you had only 2 days, here's what I'd prioritize"
- **Progress Tracking** - Help attendees remember what they've seen and what's left
- **Post-Conference** - Suggest follow-ups, connect with people met, resources to review

---

## Constraints & Limitations

### Known Constraints

1. **Dynamic Session Catalog** - The full session catalog requires JavaScript to load. Recommendations are topic-based rather than specific session titles until confirmed on the website.
2. **Real-Time Availability** - Session rooms have first-come, first-seated basis. Recommend backup options.
3. **Schedule Changes** - Conference may change session times; always verify on official site before committing.
4. **Networking Unpredictability** - Schedule can be disrupted by spontaneous connections; build in flexibility.

### What This Skill Does NOT Do

- Does not book sessions or reserve spots
- Does not provide real-time room availability
- Does not handle ticketing or registration
- Does not provide travel/hotel information (refer to travel guide)
- Does not recommend food beyond general strategy

---

## Example Use Cases

### Use Case 1: AI Engineer Wanting to Learn GenAI
```
User Input:
- Role: AI Engineer
- Interests: GenAI, LLMs, Deployment
- Level: Intermediate
- Goal: Learn production techniques
- Time: Full 5 days

Output:
- Day 1: Workshops on GenAI fundamentals
- Days 2-4: Deep dives on LLM training, fine-tuning, inference optimization
- Scattered networking and demo booths
- Boot camp on TensorRT
```

### Use Case 2: Executive Scoping for Investment
```
User Input:
- Role: VC/Executive
- Interests: Agentic AI, Enterprise Applications, Hardware
- Level: Beginner to Intermediate
- Goal: Identify trends and opportunities
- Time: 2 days (partial)

Output:
- Keynote + 2 opening sessions on Agentic AI
- Enterprise applications in healthcare/manufacturing
- Hardware announcements and roadmap
- Networking receptions
- Short-form education, more unstructured time
```

### Use Case 3: Student Exploring ML Career
```
User Input:
- Role: Student
- Interests: ML, Computer Vision, Robotics
- Level: Beginner to Intermediate  
- Goal: Career exploration and mentorship
- Time: Full 5 days

Output:
- Boot camps for fundamentals
- Broad survey of ML topics
- Startup track and VC sessions
- "Connect with the Experts" sessions
- Networking and career fair opportunities
```

---

## Prompt Template for Use

When a user wants to create their GTC 2026 game plan, use this flow:

```
🎯 GTC 2026 SCHEDULE BUILDER
───────────────────────────

Let me help you create the perfect game plan for NVIDIA GTC 2026!

I'll ask you a few quick questions to understand your interests and goals:

[Present Interest Discovery Questions - see section 1]

[Build Schedule - see section 3]

[Present Output - see section 5]

Would you like to:
- Adjust the schedule (more/less of certain topics)?
- Add more networking time?
- See backup options?
- Get specific session recommendations?
```

---

## Success Metrics

This skill succeeds when:

- ✅ User has a clear, feasible schedule for their time at GTC
- ✅ Schedule aligns with stated goals and interests
- ✅ User feels prepared and excited about the conference
- ✅ Schedule includes balanced learning, networking, and rest
- ✅ User has backup options and flexibility
- ✅ Recommendations respect realistic constraints (session limits, travel time)

---

## Tips for Best Results

1. **Be Specific About Goals** - "Learn about LLM inference" vs "I'm interested in AI"
2. **Mention Your Role** - Context helps prioritize business vs. technical sessions
3. **Be Honest About Availability** - Partial attendance is fine; schedule accordingly
4. **Ask for Adjustments** - The initial plan is a starting point, not final
5. **Check the Website** - Use the live catalog to confirm session details and times
6. **Plan for Flexibility** - Best sessions get crowded; have backups ready

---

## Resources

- **GTC Website**: https://www.nvidia.com/gtc/
- **Session Catalog**: https://www.nvidia.com/gtc/session-catalog/
- **Conference Schedule**: https://www.nvidia.com/gtc/conference-schedule/
- **Speakers**: https://www.nvidia.com/gtc/speakers/
- **Travel & Venue**: https://www.nvidia.com/gtc/travel-and-venue/
- **Training & Workshops**: https://www.nvidia.com/gtc/training/

---

## Version History

**v1.0** (March 2026)
- Initial release
- Interest discovery and mapping
- Day-by-day schedule building
- Multi-level recommendations (beginner/intermediate/expert)
- Goal-based game planning
- Conflict resolution and backup suggestions
- Networking and strategy recommendations

---

## Usage Example

```
User: "Help me plan my GTC schedule. I'm a data scientist interested in LLMs and RAG."