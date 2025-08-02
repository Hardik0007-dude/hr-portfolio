# hr-portfolio
import streamlit as st

# Page Configuration
st.set_page_config(page_title="Hardik Mattray | HR Portfolio", page_icon="💼", layout="wide")

# Custom CSS for Navy-Black-Gray Theme
st.markdown("""
    <style>
    body {
        background-color: #0b0c10; /* Black base */
        color: #e5e5e5;  /* Light gray text */
    }
    .title {
        font-size: 42px;
        font-weight: bold;
        color: #1f3a93; /* Navy blue for title */
    }
    .subtitle {
        font-size: 22px;
        color: #cccccc; /* Soft gray for subtitle */
    }
    .section {
        font-size: 26px;
        color: #1f3a93; /* Navy section headers */
        margin-top: 30px;
        font-weight: bold;
    }
    hr {
        border: 1px solid #333333; /* Dark gray separators */
    }
    </style>
""", unsafe_allow_html=True)

# Header Section
st.markdown("<div class='title'>Hardik Mattray</div>", unsafe_allow_html=True)
st.markdown("<div class='subtitle'>HR Professional | MBA (HR & Marketing) | Talent Acquisition | Employee Engagement</div>", unsafe_allow_html=True)

st.write("<hr>", unsafe_allow_html=True)

# About Me
st.markdown("<div class='section'>👨‍💼 Professional Summary</div>", unsafe_allow_html=True)
st.write("""
Motivated and ambitious **MBA (HR & Marketing)** candidate with hands-on experience in 
talent acquisition, HR operations, and workforce engagement.  
Known for driving inclusive hiring strategies, executing data-informed recruitment plans, and 
maintaining strong vendor and team collaboration.  
**Committed to becoming a recognized HR leader.**
""")

# Experience
st.markdown("<div class='section'>💼 Internship Experience</div>", unsafe_allow_html=True)
st.write("""
**HR Intern – Manupatra Information Solutions Pvt. Ltd.** (Mar 2025 – Jul 2025)  
- Diversified hiring, conflict resolution, and employee engagement.  
- Scheduled virtual interviews, managed trackers (Outlook, Calendly).  
- Assisted with attendance management, vendor coordination, and exit interviews.  

**HR Intern – Aditya Birla Capital / Sun Life Insurance** (Aug 2024 – Oct 2024)  
- Supported sourcing, screening, and onboarding processes.  
- Created recruitment dashboards and managed candidate follow-ups.  
""")

# Projects
st.markdown("<div class='section'>📂 Projects</div>", unsafe_allow_html=True)
st.write("""
- **WhatsApp in HR – Transforming Recruitment and Workforce Management**  
- **From Hypothesis to Hire – Strategic Hiring Frameworks using Data Analytics & AI**  
- **DIGIYARN – Digital Marketing Agency (HR Branding & Outreach)**  
- **ATS Optimization in Food Industry – Improved recruitment cycle**  
""")

# Skills
st.markdown("<div class='section'>🛠 Core Competencies</div>", unsafe_allow_html=True)
st.write("""
- Talent Acquisition & Resume Screening  
- Virtual Interviewing & Employee Engagement  
- HR Operations (Conflict & Attendance Management)  
- Vendor/Consultant Coordination  
- Tools: MS Office, Outlook, Calendly, Canva, AI Tools, Tally ERP.9  
- **Microsoft Certified Excel Associate**  
""")

# Leadership & Engagement
st.markdown("<div class='section'>🌟 Leadership & Engagement</div>", unsafe_allow_html=True)
st.write("""
- Vice President – HR Club: Organized HR summits, panels, and student events.  
- Council Member – Newsletter Committee: Wrote & edited departmental articles.  
- Member – CIC Committee: Supported student placements and coordination.  
""")

# Certifications
st.markdown("<div class='section'>📜 Certifications</div>", unsafe_allow_html=True)
st.write("""
- Lean Six Sigma Yellow Belt – Sparen & Gewinn, CSSC  
- Microsoft Certified Excel Associate – Microsoft  
- CCC Certification – NIELIT (Grade A)  
- Tally ERP.9 (Grade A)  
- PowerPoint using AI & ChatGPT – Skill Nation  
- AI Tools Training – be10X  
""")

# Extra-Curricular
st.markdown("<div class='section'>🎭 Extra-Curricular Highlights</div>", unsafe_allow_html=True)
st.write("""
- DIGIYARN Business Pitch – Proposed HR tech solution.  
- Ad MAD Show – Team leader for creative concept.  
- Samanvaya – Mental health awareness organizer.  
- Dasvidaniya – Coordinated farewell event.  
- The Freshers 2K24 – Event management core team.  
- Sports Competitions – Pratispardha participant.  
""")

# Education
st.markdown("<div class='section'>🎓 Education</div>", unsafe_allow_html=True)
st.write("""
- **MBA in HR & Marketing** – GNIOT, Greater Noida (2023–2025)  
- **Bachelor of Arts (BA)** – Swami Vivekanand Subharti University, Meerut (2020–2023)  
""")

# Contact Section
st.markdown("<div class='section'>📬 Contact</div>", unsafe_allow_html=True)
st.write("""
- 📍 Location: Greater Noida, U.P, India  
- 📧 Email: hardiksh019@gmail.com  
- 📱 Phone: +91 8700677835  
- 🔗 [LinkedIn](https://www.linkedin.com/in/hardik-mattray-aa263322b)  
""")
