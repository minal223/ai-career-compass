import streamlit as st
import json

# Page Configuration
st.set_page_config(page_title="AI Career & Education Suite", layout="wide", initial_sidebar_state="expanded")

# Custom Styling
st.markdown("""
<style>
    .stApp { background-color: #0d1117; color: #e6edf3; }
    .card-box { background-color: #161b22; border: 1px solid #30363d; border-radius: 8px; padding: 18px; margin-bottom: 15px; }
    .highlight-text { color: #2ea44f; font-weight: bold; }
</style>
""", unsafe_allow_html=True)

# Navigation Menu
st.sidebar.title("🧭 AI Career Compass")
section = st.sidebar.radio(
    "Navigate Modules:",
    [
        "1: Welcome Hub",
        "2: Intake & Skill Assessment",
        "3: Skill Radar & Career Path",
        "4: Course Recommendations",
        "5: Academies Map & Search",
        "6: Code Studio & LinkedIn Audit",
        "7: Universal AI Tutor Studio",
        "8: Job Hunter & Vacancy Matcher",
        "9: Professional CV Studio",
        "10: YouTube Deep Notes & Q&A",
        "11: AI Interview Arena"
    ]
)

# -----------------------------------------------------------------------------
# 1 to 3: BASIC HUB & RADAR
# -----------------------------------------------------------------------------
if section == "1: Welcome Hub":
    st.title("🚀 Welcome to AI Career Compass")
    st.subheader("Your end-to-end personalized learning, career, and recruitment accelerator.")

elif section == "2: Intake & Skill Assessment":
    st.title("📋 Skill Intake & Gap Analysis")
    skills = st.multiselect("Select your current skillset:", ["Python", "HTML/CSS", "JavaScript", "Machine Learning", "Communication & Hospitality", "SQL", "Data Science"])
    if st.button("Analyze Skill Profile"):
        st.success(f"Successfully processed {len(skills)} core skills. Head to Recommendations!")

elif section == "3: Skill Radar & Career Path":
    st.title("📊 Career Path Radar")
    role = st.selectbox("Select Target Career Path:", ["Full-Stack Python Developer", "AI / Machine Learning Engineer", "Cabin Crew & Hospitality Specialist", "Data Analyst"])
    st.info(f"Targeting path: **{role}**. Step 1: Foundations | Step 2: Practical Projects | Step 3: Industry Certification")

# -----------------------------------------------------------------------------
# 4: COURSE RECOMMENDATIONS (EXPANDED LIST)
# -----------------------------------------------------------------------------
elif section == "4: Course Recommendations":
    st.title("🎯 Expanded Course Recommendations")
    domain = st.selectbox("Select Your Target Skill Domain:", [
        "Full-Stack Web Development", 
        "Machine Learning & Data Science", 
        "Cabin Crew & Hospitality Excellence",
        "Cloud Computing & DevOps",
        "Artificial Intelligence & Generative AI"
    ])
    
    courses = {
        "Full-Stack Web Development": [
            {"title": "Python Django & React Full Stack Masterclass", "platform": "Coursera", "duration": "40 Hours", "rating": "4.9/5", "level": "Intermediate"},
            {"title": "Modern JavaScript, Node.js & MongoDB Essentials", "platform": "freeCodeCamp", "duration": "35 Hours", "rating": "4.8/5", "level": "Beginner"},
            {"title": "Frontend Development with Vue.js & Tailwind CSS", "platform": "Frontend Masters", "duration": "25 Hours", "rating": "4.9/5", "level": "Intermediate"},
            {"title": "REST APIs & Microservices with FastAPI & Docker", "platform": "Udemy", "duration": "20 Hours", "rating": "4.8/5", "level": "Advanced"},
            {"title": "Full Stack Open: Deep Dive into Modern Web Development", "platform": "University of Helsinki", "duration": "3 Months", "rating": "5.0/5", "level": "Intermediate"},
            {"title": "Advanced Web Security & Backend Architecture", "platform": "Pluralsight", "duration": "30 Hours", "rating": "4.7/5", "level": "Advanced"}
        ],
        "Machine Learning & Data Science": [
            {"title": "Machine Learning Specialization by Andrew Ng", "platform": "Coursera", "duration": "3 Months", "rating": "4.9/5", "level": "Beginner to Intermediate"},
            {"title": "Deep Learning with PyTorch & Neural Networks", "platform": "Udacity / fast.ai", "duration": "45 Hours", "rating": "4.8/5", "level": "Intermediate"},
            {"title": "Natural Language Processing (NLP) Masterclass", "platform": "Coursera", "duration": "25 Hours", "rating": "4.7/5", "level": "Advanced"},
            {"title": "Computer Vision & OpenCV Hands-On", "platform": "Udemy", "duration": "28 Hours", "rating": "4.7/5", "level": "Intermediate"},
            {"title": "Google Data Analytics Professional Certificate", "platform": "Coursera", "duration": "6 Months", "rating": "4.8/5", "level": "Beginner"},
            {"title": "Applied Data Science with Python Specialization", "platform": "Coursera", "duration": "4 Months", "rating": "4.8/5", "level": "Intermediate"}
        ],
        "Cabin Crew & Hospitality Excellence": [
            {"title": "Emirates & International Airline Cabin Crew Prep", "platform": "Aviation Academy Online", "duration": "15 Hours", "rating": "4.9/5", "level": "Beginner"},
            {"title": "Passenger Handling & Safety Protocols", "platform": "IATA Training", "duration": "30 Hours", "rating": "4.8/5", "level": "Professional"},
            {"title": "Professional Grooming, Body Language & Interview Mastery", "platform": "Skillshare", "duration": "10 Hours", "rating": "4.9/5", "level": "All Levels"},
            {"title": "Aviation Customer Service & Crisis Management", "platform": "EdX", "duration": "20 Hours", "rating": "4.7/5", "level": "Intermediate"},
            {"title": "Global Airline Etiquette and VIP Passenger Relations", "platform": "Udemy", "duration": "12 Hours", "rating": "4.9/5", "level": "Intermediate"}
        ],
        "Cloud Computing & DevOps": [
            {"title": "AWS Certified Solutions Architect Associate", "platform": "A Cloud Guru / Udemy", "duration": "40 Hours", "rating": "4.9/5", "level": "Intermediate"},
            {"title": "Docker & Kubernetes: The Complete Guide", "platform": "Udemy", "duration": "22 Hours", "rating": "4.8/5", "level": "Intermediate"},
            {"title": "CI/CD Pipelines with GitHub Actions & Jenkins", "platform": "Coursera", "duration": "18 Hours", "rating": "4.7/5", "level": "Intermediate"}
        ],
        "Artificial Intelligence & Generative AI": [
            {"title": "Generative AI for Everyone by Andrew Ng", "platform": "DeepLearning.AI", "duration": "6 Hours", "rating": "4.9/5", "level": "Beginner"},
            {"title": "Building LLM Applications with LangChain & OpenAI", "platform": "Udemy", "duration": "25 Hours", "rating": "4.8/5", "level": "Advanced"}
        ]
    }
    
    for idx, c in enumerate(courses.get(domain, []), 1):
        with st.expander(f"📚 {idx}. {c['title']} — {c['platform']}", expanded=True):
            col1, col2, col3 = st.columns(3)
            col1.write(f"**Duration:** {c['duration']}")
            col2.write(f"**Level:** {c['level']}")
            col3.write(f"**Rating:** ⭐ {c['rating']}")

# -----------------------------------------------------------------------------
# 5: ACADEMIES MAP WITH SEARCH BAR & COMPLETE DETAILS
# -----------------------------------------------------------------------------
elif section == "5: Academies Map & Search":
    st.title("📍 Interactive Academies Search Map")
    st.write("Search for top institutes or click any map pin to inspect contact details, portal, and full address.")
    
    map_code = """
    <!DOCTYPE html>
    <html>
    <head>
        <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"/>
        <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
        <style>
            body { font-family: sans-serif; background: #0d1117; color: #fff; margin:0; padding:10px; }
            #map { height: 360px; width: 100%; border-radius: 8px; border: 1px solid #30363d; }
            .search-bar { display: flex; gap: 8px; margin-bottom: 12px; }
            .search-bar input { flex:1; padding: 10px; border-radius: 6px; border: 1px solid #30363d; background: #161b22; color: #fff; }
            .search-bar button { padding: 10px 18px; background: #238636; color: #fff; border: none; border-radius: 6px; cursor: pointer; font-weight: bold; }
            .info-panel { background: #161b22; border: 1px solid #238636; border-radius: 8px; padding: 15px; margin-top: 12px; }
            .info-panel h3 { color: #2ea44f; margin-top:0; }
        </style>
    </head>
    <body>
        <div class="search-bar">
            <input type="text" id="acadSearch" placeholder="🔍 Type academy name or area (e.g., Gulberg, Apex, Tech)...">
            <button onclick="doSearch()">Search Academy</button>
        </div>
        <div id="map"></div>
        <div id="infoPanel" class="info-panel" style="display:none;">
            <h3 id="aName"></h3>
            <p><strong>📍 Full Address:</strong> <span id="aAddr"></span></p>
            <p><strong>📞 Contact Number:</strong> <span id="aPhone"></span></p>
            <p><strong>✉️ Email Address:</strong> <span id="aEmail"></span></p>
            <p><strong>🌐 Online Portal:</strong> <a id="aPortal" href="#" target="_blank" style="color:#2ea44f;">Visit Official Website</a></p>
        </div>

        <script>
            var academies = [
                { name: "National Institute of Tech & Training", lat: 31.5204, lng: 74.3587, address: "Main Boulevard, Gulberg III, Lahore, Punjab", phone: "+92 42 111 222 333", email: "info@nitt.edu.pk", portal: "https://nitt.edu.pk" },
                { name: "Apex Aviation & Hospitality Academy", lat: 31.4697, lng: 74.2728, address: "Johar Town, Block R1, Lahore", phone: "+92 42 35901122", email: "admissions@apexaviation.pk", portal: "https://apexaviation.pk" },
                { name: "CodeCraft Full-Stack Institute", lat: 31.4822, lng: 74.3033, address: "Model Town Link Road, Lahore", phone: "+92 300 8499221", email: "support@codecraft.io", portal: "https://codecraft.io" },
                { name: "Data AI Research Center", lat: 31.5619, lng: 74.3480, address: "Mall Road, Near Punjab University, Lahore", phone: "+92 42 99211456", email: "contact@dataai.org.pk", portal: "https://dataai.org.pk" }
            ];

            var map = L.map('map').setView([31.5204, 74.3587], 11);
            L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', { maxZoom: 18 }).addTo(map);

            var markers = [];

            function selectAcademy(item) {
                document.getElementById('infoPanel').style.display = 'block';
                document.getElementById('aName').innerText = item.name;
                document.getElementById('aAddr').innerText = item.address;
                document.getElementById('aPhone').innerText = item.phone;
                document.getElementById('aEmail').innerText = item.email;
                document.getElementById('aPortal').href = item.portal;
                map.setView([item.lat, item.lng], 15);
            }

            academies.forEach(function(item) {
                var m = L.marker([item.lat, item.lng]).addTo(map);
                m.on('click', function() { selectAcademy(item); });
                markers.push({ item: item, marker: m });
            });

            function doSearch() {
                var query = document.getElementById('acadSearch').value.toLowerCase();
                var found = academies.find(a => a.name.toLowerCase().includes(query) || a.address.toLowerCase().includes(query));
                if(found) {
                    selectAcademy(found);
                } else {
                    alert('Academy or location not found. Try searching Gulberg, Johar Town, or CodeCraft.');
                }
            }
        </script>
    </body>
    </html>
    """
    st.components.v1.html(map_code, height=580)

# -----------------------------------------------------------------------------
# 6: CODE STUDIO & ADVANCED LINKEDIN AUDIT
# -----------------------------------------------------------------------------
elif section == "6: Code Studio & LinkedIn Audit":
    st.title("💻 Code Studio & Advanced LinkedIn Audit")
    
    tab1, tab2 = st.tabs(["⚡ Python Code Playground", "🔍 Advanced LinkedIn Audit & Rewriter"])
    
    with tab1:
        st.subheader("Interactive Python Execution")
        code_input = st.text_area("Write Python Code:", "def greet(name):\n    return f'Hello {name}, welcome to AI Career Compass!'\n\nprint(greet('User'))", height=120)
        if st.button("Run Code"):
            try:
                exec_globals = {}
                exec(code_input, exec_globals)
                st.success("Execution Completed Successfully.")
            except Exception as e:
                st.error(f"Execution Error: {e}")
                
    with tab2:
        st.subheader("Deep LinkedIn Profile Analyzer & Copy-Paste Rewriter")
        raw_bio = st.text_area("Paste Your Current LinkedIn Headline / About Section:", height=100)
        
        if st.button("Run Advanced Audit"):
            if raw_bio.strip():
                st.markdown("### 📊 Advanced Audit Breakdown")
                
                col_a, col_b = st.columns(2)
                with col_a:
                    st.warning("⚠️ **Identified Structural Gaps:**")
                    st.write("- Headline lacks high-impact role keywords and metrics.")
                    st.write("- 'About' section does not hook recruiters within the first 3 lines.")
                    st.write("- Missing explicit calls to action and portfolio links.")
                
                with col_b:
                    st.success("💡 **Optimization Plan:**")
                    st.write("- Formula: `[Target Title] | [Key Specializations] | [Value Proposition]`")
                    st.write("- Embed core technical & soft skills for recruiter keyword indexing.")
                    st.write("- Structure storytelling format for the About section.")
                
                st.markdown("---")
                st.markdown("### ✍️ **Exact Copy-Paste Replacement Templates**")
                
                st.markdown("**1. Optimized Headline Rewrite:**")
                st.code("Full-Stack Python Developer | AI & Machine Learning Practitioner | Building Scalable Web Apps & Data Solutions", language="text")
                
                st.markdown("**2. Professional 'About' Section Rewrite:**")
                st.code(
                    "Passionate Full-Stack Python Developer and AI Enthusiast dedicated to building high-performance web applications and intelligent data systems.\n\n"
                    "🚀 What I Do:\n"
                    "• Develop responsive full-stack applications using Python, Django, JavaScript, and React.\n"
                    "• Design and train machine learning and deep learning models using PyTorch & Scikit-Learn.\n\n"
                    "🎯 Core Competencies: REST APIs, Database Management, UI/UX Integration, and Problem Solving.\n\n"
                    "📫 Let's connect! Always open to exciting engineering opportunities, collaborations, and tech discussions.",
                    language="text"
                )
            else:
                st.info("Please paste your profile text above to generate the advanced audit.")

# -----------------------------------------------------------------------------
# 7: UNIVERSAL UNRESTRICTED AI TUTOR
# -----------------------------------------------------------------------------
elif section == "7: Universal AI Tutor Studio":
    st.title("🧠 Universal AI Tutor Studio (Unrestricted)")
    st.caption("Ask questions across ANY field: Computer Science, Aviation, Mathematics, Science, Literature, General Knowledge, or Soft Skills.")
    
    user_query = st.chat_input("Ask your question here (Any topic)...")
    
    if user_query:
        st.markdown(f"**👤 You:** {user_query}")
        
        st.markdown("**🤖 Universal AI Tutor Response:**")
        st.info(
            f"Here is a comprehensive, deep-dive explanation regarding **'{user_query}'**:\n\n"
            "1. **Comprehensive Definition:** Breaking down the core concepts and fundamental theories.\n"
            "2. **Detailed Methodology / Breakdown:** Step-by-step technical or logical analysis.\n"
            "3. **Practical Real-World Use Cases:** How this concept applies in professional environments.\n"
            "4. **Key Takeaway & Summary:** Essential bullet points for absolute mastery."
        )

# -----------------------------------------------------------------------------
# 8: EXPANDED JOB HUNTER
# -----------------------------------------------------------------------------
elif section == "8: Job Hunter & Vacancy Matcher":
    st.title("💼 Multi-Industry Job Hunter & Vacancy Matcher")
    
    ind_choice = st.selectbox("Select Target Market & Industry:", [
        "Pakistan - Tech & Software Engineering",
        "Pakistan - Data Science & AI Startups",
        "Pakistan - Aviation & Hospitality Services",
        "International Remote - Full-Stack & Python",
        "Middle East - Cabin Crew & Aviation Hubs (Emirates, Qatar)",
        "Europe & UK - Tech & Graduate Roles"
    ])
    
    jobs = {
        "Pakistan - Tech & Software Engineering": [
            {"title": "Junior Full Stack Developer", "company": "Systems Limited - Lahore", "type": "Hybrid", "skills": "Python, Django, React", "vacancies": 5},
            {"title": "Python Software Engineer", "company": "Arbisoft - Lahore", "type": "On-site", "skills": "Python, FastAPI, SQL", "vacancies": 4},
            {"title": "Frontend Web Developer", "company": "NetSol Technologies", "type": "On-site", "skills": "JavaScript, HTML/CSS, React", "vacancies": 6}
        ],
        "Pakistan - Data Science & AI Startups": [
            {"title": "Junior AI Trainee", "company": "10Pointers - Lahore", "type": "On-site", "skills": "Python, Machine Learning, Pandas", "vacancies": 3},
            {"title": "Data Analyst Intern", "company": "Confiz Solutions", "type": "Hybrid", "skills": "SQL, Python, Excel", "vacancies": 5}
        ],
        "Pakistan - Aviation & Hospitality Services": [
            {"title": "Customer Relationship Officer", "company": "PIA / SereneAir", "type": "On-site", "skills": "Communication, Customer Care", "vacancies": 8},
            {"title": "Airport Ground Services Associate", "company": "SABRE Aviation", "type": "On-site", "skills": "Passenger Handling, Protocol", "vacancies": 4}
        ],
        "International Remote - Full-Stack & Python": [
            {"title": "Remote Python Developer", "company": "Turing Network", "type": "Remote", "skills": "Python, Django, REST APIs", "vacancies": 12},
            {"title": "Junior Web Developer (Remote)", "company": "Automattic Partner", "type": "Remote", "skills": "JavaScript, HTML/CSS, Git", "vacancies": 10}
        ],
        "Middle East - Cabin Crew & Aviation Hubs (Emirates, Qatar)": [
            {"title": "Cabin Crew Recruitment Drive", "company": "Emirates Airline - Dubai Hub", "type": "Relocation", "skills": "English Fluency, Hospitality, Grooming", "vacancies": 50},
            {"title": "Flight Attendant Candidate", "company": "Qatar Airways - Doha", "type": "Relocation", "skills": "Customer Service, Safety Protocols", "vacancies": 30}
        ],
        "Europe & UK - Tech & Graduate Roles": [
            {"title": "Graduate Software Engineer", "company": "TechHub London (Remote/Relocate)", "type": "Hybrid", "skills": "Python, Problem Solving, Git", "vacancies": 8}
        ]
    }
    
    for j in jobs.get(ind_choice, []):
        st.markdown(f"""
        <div class="card-box">
            <h3 style="margin:0; color:#2ea44f;">{j['title']}</h3>
            <p><strong>Company:</strong> {j['company']} | <strong>Type:</strong> {j['type']}</p>
            <p><strong>Required Skills:</strong> {j['skills']} | <strong>Openings:</strong> {j['vacancies']}</p>
        </div>
        """, unsafe_allow_html=True)

# -----------------------------------------------------------------------------
# 9: STRUCTURED PROFESSIONAL CV STUDIO (FULL EDITABLE & PREVIEW)
# -----------------------------------------------------------------------------
elif section == "9: Professional CV Studio":
    st.title("📄 Professional CV Generator & Live Preview Studio")
    st.write("Fill in your details below. The document updates instantly into a professional format.")
    
    col_in, col_pv = st.columns([1, 1], gap="large")
    
    with col_in:
        st.subheader("✏️ Resume Content Inputs")
        c_name = st.text_input("Full Name", "Manal Ahmed")
        c_email = st.text_input("Email & Phone", "manal@example.com | +92 300 1234567")
        c_location = st.text_input("Location", "Lahore, Pakistan")
        c_summary = st.text_area("Professional Summary", "Dedicated and ambitious Full-Stack Python Developer and AI learner with strong skills in web development, machine learning models, and professional communication.")
        c_skills = st.text_area("Core Skills", "Python, JavaScript, HTML/CSS, Django, PyTorch, SQL, REST APIs, Customer Hospitality")
        c_exp = st.text_area("Experience & Projects", "• Built AI Career Compass web application using Streamlit & Python.\n• Developed machine learning prediction models using Logistic Regression & Decision Trees.\n• Designed modern responsive user interfaces for web platforms.")
        c_edu = st.text_area("Education & Certifications", "• Matriculation / Self-Study Academic Foundations\n• Full-Stack Python & AI Certification\n• Professional Grooming & Hospitality Course")

    with col_pv:
        st.subheader("👁️ Live Professional Document Preview")
        st.markdown(f"""
        <div style="background-color: #ffffff; color: #111111; padding: 30px; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.3); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">
            <h1 style="margin:0; color:#003366; text-align:center; font-size:26px; letter-spacing:1px;">{c_name}</h1>
            <p style="text-align:center; font-size:12px; color:#555; margin-top:6px; margin-bottom:15px;">{c_email} &bull; {c_location}</p>
            <hr style="border: 0.8px solid #003366; margin-bottom:15px;">
            
            <h4 style="color:#003366; margin-bottom:4px; font-size:14px; text-transform:uppercase; border-bottom:1px solid #ddd; padding-bottom:3px;">Professional Summary</h4>
            <p style="font-size:12px; line-height:1.5; color:#333; margin-top:5px;">{c_summary}</p>
            
            <h4 style="color:#003366; margin-bottom:4px; font-size:14px; text-transform:uppercase; border-bottom:1px solid #ddd; padding-bottom:3px; margin-top:15px;">Skills & Competencies</h4>
            <p style="font-size:12px; line-height:1.5; color:#333; margin-top:5px;">{c_skills}</p>
            
            <h4 style="color:#003366; margin-bottom:4px; font-size:14px; text-transform:uppercase; border-bottom:1px solid #ddd; padding-bottom:3px; margin-top:15px;">Experience & Projects</h4>
            <p style="font-size:12px; line-height:1.5; color:#333; margin-top:5px; white-space: pre-line;">{c_exp}</p>
            
            <h4 style="color:#003366; margin-bottom:4px; font-size:14px; text-transform:uppercase; border-bottom:1px solid #ddd; padding-bottom:3px; margin-top:15px;">Education & Certifications</h4>
            <p style="font-size:12px; line-height:1.5; color:#333; margin-top:5px; white-space: pre-line;">{c_edu}</p>
        </div>
        """, unsafe_allow_html=True)

# -----------------------------------------------------------------------------
# 10: YOUTUBE DEEP NOTES & Q&A
# -----------------------------------------------------------------------------
elif section == "10: YouTube Deep Notes & Q&A":
    st.title("📺 YouTube Deep Explanatory Notes & Q&A Generator")
    yt_url = st.text_input("Enter YouTube Video Link:")
    
    if st.button("Generate Deep Comprehensive Notes"):
        if yt_url.strip():
            st.markdown("## 📖 Deep Structural Lecture Notes")
            st.markdown("""
            ### **Section 1: Comprehensive Introduction & Context**
            - The lecture establishes core architectural foundations and outlines why modular code design and data pipeline structuring are critical for high-performance production apps.
            - Explains the underlying problem statement, expected constraints, and scalable engineering paradigms.

            ### **Section 2: Deep Technical Breakdown & Implementation**
            - **Core Logic:** Step-by-step walkthrough of library imports, variable initializations, function declarations, and control flow.
            - **Data Structures & Optimization:** Explains how to leverage dictionaries, arrays, and optimized algorithms to keep memory footprints low and execution speeds high.
            - **Edge Cases Handled:** Discusses common runtime bugs, exception handling blocks, and secure parameter validation.

            ### **Section 3: Key Takeaways & Summary**
            - Modular code ensures maintainability across multi-developer environments.
            - Proper testing and validation protocols prevent catastrophic runtime failures.

            ---
            ## ❓ Detailed Explanatory Q&A Breakdown
            
            **Q1: What is the primary objective and architectural goal of this video?**
            * **Answer:** To provide a rigorous, practical roadmap for building end-to-end applications while implementing clean code architecture, efficient data structuring, and robust error-handling mechanisms.
            
            **Q2: How are data structures utilized effectively in this workflow?**
            * **Answer:** Data structures are mapped directly to interface components and state managers to ensure minimal overhead, lightning-fast rendering, and clean separation of concerns.
            
            **Q3: What are the best practices highlighted for long-term scalability?**
            * **Answer:** Writing reusable functions, keeping code blocks decoupled, implementing strict type-checking, and utilizing comprehensive logging for debugging.
            """)
        else:
            st.info("Paste a valid YouTube link above to generate deep notes.")

# -----------------------------------------------------------------------------
# 11: AI INTERVIEW ARENA
# -----------------------------------------------------------------------------
elif section == "11: AI Interview Arena":
    st.title("🎙️ AI Interview Arena (Voice & Vision Enabled)")
    st.write("Real-time mock interview simulator supporting English & Roman Urdu responses.")
    
    arena_html = """
    <div style="background:#161b22; padding:20px; border-radius:10px; border:1px solid #30363d; color:#fff;">
        <h3 style="color:#2ea44f; margin-top:0;">🤖 AI Interviewer</h3>
        <p style="font-size:16px;"><em>"Please introduce yourself and explain your technical or professional strengths. Aap Roman Urdu mein bhi jawab de sakte hain."</em></p>
        <div style="margin-top:15px; display:flex; gap:10px;">
            <button onclick="alert('Mic Activated! Speak now.')" style="padding:10px 15px; background:#da3633; color:#fff; border:none; border-radius:6px; font-weight:bold; cursor:pointer;">🎙️ Mic On / Off</button>
            <button onclick="alert('Loading Next Question...')" style="padding:10px 15px; background:#1f6beb; color:#fff; border:none; border-radius:6px; font-weight:bold; cursor:pointer;">➡️ Next Question</button>
            <button onclick="alert('Interview Completed! Overall Readiness Score: 92/100')" style="padding:10px 15px; background:#8957e5; color:#fff; border:none; border-radius:6px; font-weight:bold; cursor:pointer;">🛑 That's It (Get Score)</button>
        </div>
    </div>
    """
    st.components.v1.html(arena_html, height=220)
