import streamlit as st

# --------------------------------------------------
# PAGE CONFIGURATION
# --------------------------------------------------

st.set_page_config(
    page_title="Nikitha Bairu | Data Analyst",
    page_icon="📊",
    layout="wide",
    initial_sidebar_state="collapsed"
)

# --------------------------------------------------
# CUSTOM CSS
# --------------------------------------------------

st.markdown("""
<style>

@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Space+Grotesk:wght@500;600;700&display=swap');

html, body, [class*="css"] {
    font-family: 'DM Sans', sans-serif;
}

.stApp {
    background-color: #07100d;
    color: #f0fff7;
}

/* Remove Streamlit top padding */
.block-container {
    padding-top: 2rem;
    max-width: 1150px;
}

/* Main headings */
h1, h2, h3 {
    font-family: 'Space Grotesk', sans-serif;
}

/* Hero */
.hero {
    padding: 90px 0 80px 0;
}

.small-title {
    color: #64f3ad;
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 2px;
}

.hero-title {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 70px;
    font-weight: 700;
    line-height: 1.0;
    letter-spacing: -3px;
    margin-top: 20px;
}

.green {
    color: #64f3ad;
}

.hero-description {
    color: #9cafaa;
    font-size: 18px;
    line-height: 1.7;
    max-width: 650px;
    margin-top: 25px;
}

/* Buttons */
.button {
    display: inline-block;
    padding: 13px 22px;
    margin-top: 25px;
    margin-right: 10px;
    border-radius: 8px;
    text-decoration: none !important;
    font-weight: 700;
}

.primary-button {
    background-color: #64f3ad;
    color: #06120c !important;
}

.secondary-button {
    border: 1px solid #30443b;
    color: white !important;
}

/* Cards */
.card {
    background-color: #0d1a15;
    border: 1px solid #20342c;
    border-radius: 15px;
    padding: 28px;
    margin-bottom: 20px;
}

.card:hover {
    border-color: #64f3ad;
}

.card-title {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 22px;
    font-weight: 700;
    margin-bottom: 10px;
}

.card-text {
    color: #9cafaa;
    line-height: 1.7;
}

/* Section */
.section {
    padding: 80px 0;
    border-top: 1px solid #182720;
}

.section-label {
    color: #64f3ad;
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 2px;
}

.section-title {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 48px;
    font-weight: 700;
    margin-top: 10px;
    margin-bottom: 40px;
}

/* Skills */
.skill {
    background: #0d1a15;
    border: 1px solid #20342c;
    border-radius: 12px;
    padding: 22px;
    margin-bottom: 15px;
}

.skill-icon {
    font-size: 28px;
}

.skill-title {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 19px;
    font-weight: 700;
    margin-top: 10px;
}

.skill-text {
    color: #9cafaa;
    font-size: 14px;
    line-height: 1.6;
}

/* Project */
.project-number {
    color: #64f3ad;
    font-size: 35px;
    font-weight: 700;
}

.project-category {
    color: #64f3ad;
    font-size: 12px;
    letter-spacing: 1.5px;
    font-weight: 700;
}

.project-title {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 28px;
    font-weight: 700;
}

.project-description {
    color: #9cafaa;
    line-height: 1.7;
}

/* Tags */
.tag {
    display: inline-block;
    border: 1px solid #294238;
    color: #b8ffda;
    border-radius: 30px;
    padding: 5px 11px;
    margin: 4px;
    font-size: 12px;
}

/* Contact */
.contact {
    background-color: #64f3ad;
    color: #06120c;
    padding: 70px;
    border-radius: 20px;
    margin-top: 50px;
}

.contact-title {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 48px;
    font-weight: 700;
}

/* Footer */
.footer {
    text-align: center;
    color: #71847c;
    padding: 40px 0;
}

/* Mobile */
@media (max-width: 768px) {

    .hero-title {
        font-size: 45px;
    }

    .section-title {
        font-size: 36px;
    }

    .contact {
        padding: 35px;
    }

    .contact-title {
        font-size: 35px;
    }
}

</style>
""", unsafe_allow_html=True)


# --------------------------------------------------
# HERO SECTION
# --------------------------------------------------

st.markdown("""
<div class="hero">

<p class="small-title">
DATA ANALYST • TELANGANA, INDIA
</p>

<div class="hero-title">
Turning <span class="green">Data</span><br>
Into Insights.
</div>

<p class="hero-description">
Hi, I'm <strong>Nikitha Bairu</strong>, a detail-oriented Data Analyst
with hands-on experience in SQL, Python, Excel and Power BI.
I enjoy transforming complex datasets into meaningful insights
that support better decision-making.
</p>

<a class="button primary-button"
href="#projects">
View Projects
</a>

<a class="button secondary-button"
href="mailto:nikithamudhiraj@gmail.com">
Contact Me
</a>

</div>
""", unsafe_allow_html=True)


# --------------------------------------------------
# ABOUT
# --------------------------------------------------

st.markdown("""
<div class="section">

<p class="section-label">
01 — ABOUT ME
</p>

<div class="section-title">
Curious about what the numbers are saying.
</div>

</div>
""", unsafe_allow_html=True)

col1, col2 = st.columns(2)

with col1:

    st.markdown("""
    <div class="card">

    <div class="card-title">
    Data Analyst
    </div>

    <div class="card-text">

    Detail-oriented Data Analyst with strong analytical skills
    and hands-on experience in SQL, Python, Excel and Power BI.

    </div>

    </div>
    """, unsafe_allow_html=True)


with col2:

    st.markdown("""
    <div class="card">

    <div class="card-title">
    My Approach
    </div>

    <div class="card-text">

    I collect, clean, analyze and visualize data to discover
    patterns, trends and actionable insights that can support
    data-driven decisions.

    </div>

    </div>
    """, unsafe_allow_html=True)


# --------------------------------------------------
# SKILLS
# --------------------------------------------------

st.markdown("""
<div class="section">

<p class="section-label">
02 — SKILLS
</p>

<div class="section-title">
My Analytics Toolkit
</div>

</div>
""", unsafe_allow_html=True)


skills = [
    (
        "🐍",
        "Python",
        "Python for data analysis, automation and exploratory data analysis."
    ),

    (
        "🗄️",
        "SQL & MySQL",
        "Querying databases, data extraction, relational database design and optimization."
    ),

    (
        "📊",
        "Power BI",
        "Dashboard development, reporting and interactive data visualization."
    ),

    (
        "📗",
        "Advanced Excel",
        "Data cleaning, validation, preparation, analysis and reporting."
    ),

    (
        "🔢",
        "Pandas & NumPy",
        "Data manipulation, numerical analysis and working with large datasets."
    ),

    (
        "📈",
        "Business Analytics",
        "Campaign analytics, customer engagement, trend analysis and customer response analysis."
    )
]

skill_columns = st.columns(3)

for index, skill in enumerate(skills):

    icon, title, description = skill

    with skill_columns[index % 3]:

        st.markdown(f"""
        <div class="skill">

        <div class="skill-icon">
        {icon}
        </div>

        <div class="skill-title">
        {title}
        </div>

        <div class="skill-text">
        {description}
        </div>

        </div>
        """, unsafe_allow_html=True)


# --------------------------------------------------
# PROJECTS
# --------------------------------------------------

st.markdown("""
<div class="section" id="projects">

<p class="section-label">
03 — PROJECTS
</p>

<div class="section-title">
Selected Projects
</div>

</div>
""", unsafe_allow_html=True)


# PROJECT 1

col1, col2 = st.columns([1, 5])

with col1:

    st.markdown("""
    <div class="project-number">
    01
    </div>
    """, unsafe_allow_html=True)

with col2:

    st.markdown("""
    <div class="project-category">
    DATA ANALYSIS · SOCIAL NETWORKS
    </div>

    <div class="project-title">
    Stress Detection Based on Social Interactions
    in Social Networks
    </div>

    <div class="project-description">

    Collected, cleaned and prepared social network interaction
    data for analytical modeling and pattern identification.

    <br><br>

    • Performed exploratory data analysis using Python.<br>
    • Identified behavioral trends associated with stress indicators.<br>
    • Generated analytical reports and visualizations.<br>
    • Extracted actionable insights from large datasets.

    <br><br>

    <span class="tag">Python</span>
    <span class="tag">EDA</span>
    <span class="tag">Data Visualization</span>
    <span class="tag">Analytics</span>

    </div>
    """, unsafe_allow_html=True)


st.write("")


# PROJECT 2

col1, col2 = st.columns([1, 5])

with col1:

    st.markdown("""
    <div class="project-number">
    02
    </div>
    """, unsafe_allow_html=True)

with col2:

    st.markdown("""
    <div class="project-category">
    RESEARCH · BLOCKCHAIN
    </div>

    <div class="project-title">
    Fake News, Disinformation, and Deepfake Detection
    Using Blockchain
    </div>

    <div class="project-description">

    Analyzed large volumes of digital information to identify
    misinformation trends and content authenticity challenges.

    <br><br>

    • Conducted research-driven data analysis.<br>
    • Evaluated limitations of centralized verification systems.<br>
    • Developed structured documentation.<br>
    • Presented insights supporting technology-based solutions.

    <br><br>

    <span class="tag">Data Analysis</span>
    <span class="tag">Research</span>
    <span class="tag">Blockchain</span>
    <span class="tag">Problem Solving</span>

    </div>
    """, unsafe_allow_html=True)


# --------------------------------------------------
# EDUCATION
# --------------------------------------------------

st.markdown("""
<div class="section">

<p class="section-label">
04 — EDUCATION
</p>

<div class="section-title">
Academic Background
</div>

<div class="card">

<div class="project-category">
2021 — 2025
</div>

<div class="card-title">
Bachelor of Technology
</div>

<p>
<strong>Computer Science Engineering</strong>
</p>

<p class="card-text">
Priyadarshini Institute of Science and Technology, Khammam
</p>

<br>

<p>
CGPA: <strong style="color:#64f3ad;">7.0 / 10</strong>
</p>

</div>

</div>
""", unsafe_allow_html=True)


# --------------------------------------------------
# CERTIFICATIONS
# --------------------------------------------------

st.markdown("""
<div class="section">

<p class="section-label">
05 — CERTIFICATIONS
</p>

<div class="section-title">
Continuous Learning
</div>

</div>
""", unsafe_allow_html=True)


certifications = [
    (
        "01",
        "Python Programming Certification",
        "DevTown & Startup India"
    ),

    (
        "02",
        "Advancements in Artificial Intelligence and Applications",
        "Workshop Certification"
    ),

    (
        "03",
        "Internet of Things (IoT)",
        "Certification"
    )
]


for number, title, organization in certifications:

    st.markdown(f"""
    <div class="card">

    <span class="project-number">
    {number}
    </span>

    <div class="card-title">
    {title}
    </div>

    <div class="card-text">
    {organization}
    </div>

    </div>
    """, unsafe_allow_html=True)


# --------------------------------------------------
# CONTACT
# --------------------------------------------------

st.markdown("""
<div class="contact">

<p style="font-size:12px;letter-spacing:2px;font-weight:bold;">
06 — CONTACT
</p>

<div class="contact-title">
Let's turn data into decisions.
</div>

<p style="margin-top:20px;">
I'm open to opportunities, collaborations,
and conversations about data analytics.
</p>

<br>

<strong>Email</strong>

<br>

<a href="mailto:nikithamudhiraj@gmail.com">
nikithamudhiraj@gmail.com
</a>

<br><br>

<strong>LinkedIn</strong>

<br>

<a href="https://www.linkedin.com/in/nikitha-bairu"
target="_blank">

linkedin.com/in/nikitha-bairu

</a>

</div>
""", unsafe_allow_html=True)


# --------------------------------------------------
# FOOTER
# --------------------------------------------------

st.markdown("""
<div class="footer">

© 2026 Nikitha Bairu • Data Analyst Portfolio

</div>
""", unsafe_allow_html=True)
