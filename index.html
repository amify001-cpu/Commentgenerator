
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Comment Generator - Gold Edition</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 50%, #1a1a1a 100%);
            min-height: 100vh;
            position: relative;
        }

        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(ellipse at top right, rgba(212, 175, 55, 0.15) 0%, transparent 50%),
                radial-gradient(ellipse at bottom left, rgba(192, 192, 192, 0.12) 0%, transparent 50%);
            pointer-events: none;
            z-index: 0;
        }

        .wrapper {
            display: flex;
            min-height: 100vh;
            position: relative;
            z-index: 1;
        }

        .sidebar {
            width: 280px;
            background: linear-gradient(180deg, #0a0a0a 0%, #1a1a1a 50%, #0a0a0a 100%);
            border-right: 2px solid rgba(212, 175, 55, 0.3);
            color: #d4af37;
            padding: 30px 0;
            box-shadow: 
                4px 0 20px rgba(212, 175, 55, 0.2),
                inset -1px 0 10px rgba(212, 175, 55, 0.1);
            position: fixed;
            height: 100vh;
            overflow-y: auto;
        }

        .sidebar-title {
            font-size: 1.3em;
            font-weight: bold;
            padding: 0 20px 20px;
            border-bottom: 2px solid rgba(212, 175, 55, 0.4);
            margin-bottom: 20px;
            color: #d4af37;
            text-shadow: 0 0 10px rgba(212, 175, 55, 0.3);
            letter-spacing: 1px;
        }

        .qualification-list {
            list-style: none;
        }

        .qualification-item {
            padding: 15px 20px;
            cursor: pointer;
            transition: all 0.3s ease;
            border-left: 4px solid transparent;
            font-size: 0.95em;
            color: #c0c0c0;
        }

        .qualification-item:hover {
            background: linear-gradient(90deg, rgba(212, 175, 55, 0.15) 0%, transparent 100%);
            border-left-color: #d4af37;
            color: #d4af37;
            text-shadow: 0 0 8px rgba(212, 175, 55, 0.3);
        }

        .qualification-item.active {
            background: linear-gradient(90deg, rgba(212, 175, 55, 0.25) 0%, rgba(212, 175, 55, 0.1) 100%);
            border-left-color: #d4af37;
            font-weight: 600;
            color: #d4af37;
            box-shadow: inset 0 0 15px rgba(212, 175, 55, 0.2);
        }

        .main-content {
            margin-left: 280px;
            flex: 1;
            padding: 40px;
        }

        .container {
            background: linear-gradient(145deg, #ffffff 0%, #f5f5f5 100%);
            border-radius: 20px;
            box-shadow: 
                0 20px 60px rgba(0, 0, 0, 0.6),
                0 0 0 1px rgba(212, 175, 55, 0.2),
                inset 0 1px 0 rgba(255, 255, 255, 0.8);
            padding: 40px;
            max-width: 900px;
            margin: 0 auto;
            border: 1px solid rgba(192, 192, 192, 0.3);
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 2px solid rgba(212, 175, 55, 0.3);
        }

        .header h1 {
            color: #1a1a1a;
            font-size: 2em;
            margin-bottom: 5px;
            text-shadow: 0 2px 4px rgba(212, 175, 55, 0.2);
        }

        .header p {
            color: #666;
            font-size: 0.9em;
            margin-bottom: 15px;
        }

        .active-qual {
            display: inline-block;
            background: linear-gradient(135deg, #d4af37 0%, #aa8929 100%);
            color: #1a1a1a;
            padding: 8px 20px;
            border-radius: 20px;
            font-size: 0.85em;
            font-weight: 600;
            margin-top: 10px;
            box-shadow: 
                0 4px 15px rgba(212, 175, 55, 0.4),
                inset 0 1px 0 rgba(255, 255, 255, 0.3);
            border: 1px solid rgba(170, 137, 41, 0.5);
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #1a1a1a;
            font-size: 0.95em;
        }

        input[type="text"],
        select {
            width: 100%;
            padding: 12px;
            border: 2px solid #c0c0c0;
            border-radius: 8px;
            font-size: 1em;
            transition: all 0.3s ease;
            background: white;
        }

        textarea {
            width: 100%;
            padding: 12px;
            border: 2px solid #c0c0c0;
            border-radius: 8px;
            font-size: 1em;
            min-height: 120px;
            resize: vertical;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background: white;
        }

        input[type="text"]:focus,
        select:focus,
        textarea:focus {
            outline: none;
            border-color: #d4af37;
            box-shadow: 0 0 0 3px rgba(212, 175, 55, 0.2);
        }

        select {
            cursor: pointer;
        }

        select option[value="random"] { background: #FFF9E6; }
        select option[value="short"] { background: #E8F8F0; }
        select option[value="encouraging"] { background: #FFF5E1; }
        select option[value="detailed"] { background: #F0F0F0; }
        select option[value="growth"] { background: #EAFAF1; }
        select option[value="professional"] { background: #E8E8E8; }
        select option[value="warm"] { background: #FFF0E6; }
        select option[value="balanced"] { background: #F9F9F9; }

        .button-group {
            display: flex;
            gap: 10px;
            margin-top: 25px;
        }

        button {
            flex: 1;
            padding: 14px 20px;
            border: none;
            border-radius: 8px;
            font-size: 1em;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .btn-generate {
            background: linear-gradient(135deg, #d4af37 0%, #aa8929 100%);
            color: #1a1a1a;
            box-shadow: 
                0 4px 15px rgba(212, 175, 55, 0.4),
                inset 0 1px 0 rgba(255, 255, 255, 0.3);
            border: 1px solid rgba(170, 137, 41, 0.5);
        }

        .btn-generate:hover {
            transform: translateY(-2px);
            box-shadow: 
                0 6px 20px rgba(212, 175, 55, 0.6),
                inset 0 1px 0 rgba(255, 255, 255, 0.4);
            background: linear-gradient(135deg, #e5c158 0%, #bb9a3a 100%);
        }

        .btn-copy {
            background: linear-gradient(135deg, #c0c0c0 0%, #a0a0a0 100%);
            color: #1a1a1a;
            box-shadow: 
                0 4px 15px rgba(192, 192, 192, 0.4),
                inset 0 1px 0 rgba(255, 255, 255, 0.5);
            border: 1px solid rgba(160, 160, 160, 0.5);
        }

        .btn-copy:hover {
            transform: translateY(-2px);
            box-shadow: 
                0 6px 20px rgba(192, 192, 192, 0.6),
                inset 0 1px 0 rgba(255, 255, 255, 0.6);
            background: linear-gradient(135deg, #d0d0d0 0%, #b0b0b0 100%);
        }

        .btn-reset {
            background: linear-gradient(135deg, #2d2d2d 0%, #1a1a1a 100%);
            color: #d4af37;
            box-shadow: 
                0 4px 15px rgba(0, 0, 0, 0.4),
                inset 0 1px 0 rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(212, 175, 55, 0.3);
        }

        .btn-reset:hover {
            transform: translateY(-2px);
            box-shadow: 
                0 6px 20px rgba(0, 0, 0, 0.6),
                inset 0 1px 0 rgba(255, 255, 255, 0.15);
            background: linear-gradient(135deg, #3d3d3d 0%, #2a2a2a 100%);
        }

        .output-label {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 25px;
            margin-bottom: 8px;
        }

        .word-count {
            font-size: 0.85em;
            color: #666;
            font-weight: 600;
        }

        .success-message {
            background: linear-gradient(135deg, #d4af37 0%, #aa8929 100%);
            color: #1a1a1a;
            padding: 12px;
            border-radius: 8px;
            margin-top: 15px;
            display: none;
            text-align: center;
            font-weight: 600;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.4);
            border: 1px solid rgba(170, 137, 41, 0.5);
        }

        @media (max-width: 768px) {
            .sidebar {
                width: 100%;
                height: auto;
                position: relative;
            }
            .main-content {
                margin-left: 0;
                padding: 20px;
            }
            .container {
                padding: 25px;
            }
            .header h1 {
                font-size: 1.5em;
            }
            .button-group {
                flex-direction: column;
            }
            button {
                width: 100%;
            }
        }

        .sidebar::-webkit-scrollbar {
            width: 8px;
        }

        .sidebar::-webkit-scrollbar-track {
            background: rgba(0, 0, 0, 0.3);
            border-radius: 4px;
        }

        .sidebar::-webkit-scrollbar-thumb {
            background: linear-gradient(180deg, #d4af37 0%, #aa8929 100%);
            border-radius: 4px;
            border: 1px solid rgba(212, 175, 55, 0.3);
        }

        .sidebar::-webkit-scrollbar-thumb:hover {
            background: linear-gradient(180deg, #e5c158 0%, #bb9a3a 100%);
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="sidebar">
            <div class="sidebar-title">📚 Qualifications</div>
            <ul class="qualification-list">
                <li class="qualification-item active" onclick="selectQualification('c4es', 'Certificate 4 Education Support', this)">Certificate 4 Education Support</li>
                <li class="qualification-item" onclick="selectQualification('c3ecec', 'Certificate 3 ECEC', this)">Certificate 3 ECEC</li>
                <li class="qualification-item" onclick="selectQualification('decec', 'Diploma of ECEC', this)">Diploma of ECEC</li>
                <li class="qualification-item" onclick="selectQualification('cs', 'Diploma of Community Services', this)">Diploma of Community Services</li>
                <li class="qualification-item" onclick="selectQualification('aging-old', 'Aging Support', this)">Aging Support</li>
                <li class="qualification-item" onclick="selectQualification('aging-new', 'Aging Support (New LMS)', this)">Aging Support (New LMS)</li>
                <li class="qualification-item" onclick="selectQualification('cis', 'Certificate in Individual Support', this)">Certificate in Individual Support</li>
            </ul>
        </div>
        
        <div class="main-content">
            <div class="container">
                <div class="header">
                    <h1>📝 Comment Generator</h1>
                    <p>Assessment Task Comments</p>
                    <div class="active-qual" id="activeQual">Certificate 4 Education Support</div>
                </div>

                <div class="form-group">
                    <label for="nameInput">Learner Name:</label>
                    <input type="text" id="nameInput" placeholder="e.g. Alex Smith">
                </div>

                <div class="form-group">
                    <label for="taskSelect">Assessment Task:</label>
                    <select id="taskSelect">
                        <option value="">Select an assessment task...</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="toneSelect">Tone Filter:</label>
                    <select id="toneSelect">
                        <option value="random">🎲 Random (All Styles)</option>
                        <option value="short">⚡ Short & Direct</option>
                        <option value="encouraging">💪 Encouraging & Positive</option>
                        <option value="detailed">📋 Detailed & Specific</option>
                        <option value="growth">🌱 Growth-Focused</option>
                        <option value="professional">👔 Professional Tone</option>
                        <option value="warm">❤️ Warm & Personal</option>
                        <option value="balanced">⚖️ Balanced Feedback</option>
                    </select>
                </div>

                <div class="button-group">
                    <button class="btn-generate" id="generateBtn">Generate Comment</button>
                    <button class="btn-copy" id="copyBtn">Copy to Clipboard</button>
                    <button class="btn-reset" id="resetBtn">Reset History</button>
                </div>

                <div class="output-label">
                    <label for="output">Generated Comment:</label>
                    <span class="word-count" id="wordCount">0 words</span>
                </div>
                <textarea id="output" readonly placeholder="Your generated comment will appear here..."></textarea>

                <div class="success-message" id="successMsg">✓ Copied to clipboard!</div>
            </div>
        </div>
    </div>

    <script>
        let currentQual = 'c4es';
        let lastUsedTone = 'random';
          // COMPLETE ALL TASKS DATA FOR ALL QUALIFICATIONS
        const allTasks = {
            'c4es': [
                {code: 'CHCDIV001-AT1', name: 'Sense of Work with diverse people'},
                {code: 'CHCDIV001-AT2', name: 'Cultural Diversity in Australia'},
                {code: 'CHCDIV001-AT3', name: 'Role in Communicating with Culturally Diverse People'},
                {code: 'CHCDIV001-AT4', name: 'Reflect on Own and Other Cultures'},
                {code: 'CHCEDS033-AT1', name: 'Meet legal and ethical obligations in an education support environment'},
                {code: 'CHCEDS033-AT2', name: 'Identify and Comply with Legal and Ethical Obligations'},
                {code: 'CHCEDS033-AT3A', name: 'maintained health, safety and wellbeing standards'},
                {code: 'CHCEDS033-AT3B', name: 'completed required health, safety and wellbeing documentation'},
                {code: 'CHCEDS033-AT3C', name: 'responded to emergency situations'},
                {code: 'CHCEDS059-AT1', name: 'Contribute to the health, safety and wellbeing of students'},
                {code: 'CHCEDS059-AT2', name: 'Complete an Emergency Evacuation and Hazard Report'},
                {code: 'CHCEDS059-AT3', name: 'Educate Students About Health, Safety and Wellbeing'},
                {code: 'CHCEDS059-AT4', name: 'Health, Safety and Wellbeing Outside the Classroom'},
                {code: 'CHCEDS045-AT1', name: 'Develop and Implement Strategies to Support Maths'},
                {code: 'CHCEDS045-AT2A', name: 'assessed student knowledge and skills and built reports'},
                {code: 'CHCEDS045-AT2B', name: 'contributed to planning in consultation with the teacher'},
                {code: 'CHCEDS045-AT2C', name: 'implemented strategies and reported back to the teacher'},
                {code: 'CHCEDS046-AT1', name: 'Literacy and Learning'},
                {code: 'CHCEDS046-AT2', name: 'Learning Approaches and Practices'},
                {code: 'CHCEDS046-AT3', name: 'Facilitate Literacy Learning'},
                {code: 'CHCEDS046-AT4', name: 'Work Performance Reflections'},
                {code: 'CHCEDS046-AT5', name: 'Supervisor Report on literacy & learning ideas'},
                {code: 'CHCEDS042-AT1', name: 'Provide Support For E-Learning'},
                {code: 'CHCEDS042-AT2', name: 'E-learning Case Studies'},
                {code: 'CHCEDS042-AT3', name: 'E-learning System Research'},
                {code: 'CHCEDS042-AT4', name: 'Reflections on E-learning Experiences'},
                {code: 'CHCEDS042-AT5', name: 'Supervisor Report on E-Learning platforms'},
                {code: 'CHCEDS049-AT1', name: 'Supervise Students Outside the Classroom'},
                {code: 'CHCEDS049-AT2', name: 'Plan, Implement and Reflect on Supervision Strategies'},
                {code: 'CHCEDS049-AT2A', name: 'Complete a Risk Assessment and Management Plan For Outside The Classroom'},
                {code: 'CHCEDS049-AT2B', name: 'Assessor\'s Observations to conduct an outdoor activity'},
                {code: 'CHCEDS049-AT2C', name: 'Reflection Strategies Used for Supervision and Interaction With Children'},
                {code: 'CHCEDS049-AT2D', name: 'Complete Incident Debrief and Incident Report Documents'},
                {code: 'CHCEDS049-AT3', name: 'Supervisor Report on outdoors activity'},
                {code: 'CHCEDS053-AT1', name: 'Assist in Production of Language Resources'},
                {code: 'CHCEDS053-AT2', name: 'Produce Language Resources'},
                {code: 'CHCEDS053-AT3', name: 'Supervisor Report on language resources'},
                {code: 'CHCEDS048-AT1', name: 'Supporting Additional Needs of the child'},
                {code: 'CHCEDS048-AT2', name: 'Autism Spectrum Disorder (ASD)'},
                {code: 'CHCEDS048-AT3', name: 'Provide Additional Learning Support'},
                {code: 'CHCEDS048-AT4', name: 'Reflect on Supporting Additional Needs Students'},
                {code: 'CHCEDS058-AT1', name: 'Supporting Disability and Behaviours'},
                {code: 'CHCEDS058-AT2', name: 'Design Behaviour and Inclusion Plans'},
                {code: 'CHCEDS058-AT3', name: 'Implement Behaviour and Inclusion Plans'},
                {code: 'CHCEDS058-AT4', name: 'Behaviour and Inclusion Plans Review'},
                {code: 'CHCEDS058-AT5', name: 'Supervisor feedback for the Behaviour and inclusion plan'},
                {code: 'CHCPRP003-AT1', name: 'Reflect on and Improve own Professional Practice'},
                {code: 'CHCPRP003-AT2', name: 'Practice Improvement Research Report - Sector Developments'},
                {code: 'CHCPRP003-AT3', name: 'Feedback to Improve Practice'},
                {code: 'CHCPRP003-AT4', name: 'Personal Development Plan'},
                {code: 'CHCPRT001-AT1', name: 'Identify and Respond to Children and Young People at Risk'},
                {code: 'CHCPRT001-AT2', name: 'Justin and Heidi role play'},
                {code: 'CHCPRT001-AT3A', name: 'Disclosure of Abuse From Justin (Role play)'},
                {code: 'CHCPRT001-AT3B', name: 'Report to Supervisor and Coordinator'},
                {code: 'CHCPRT001-AT3C', name: 'Report Suspicions of Child Abuse'},
                {code: 'CHCPRT001-AT4', name: 'Portfolio of Procedures and Experiences'},
                {code: 'CHCECE054-AT1', name: 'understanding of Aboriginal and/or Torres Strait Islander'},
                {code: 'CHCECE054-AT2', name: 'Reflection about Aboriginal and/or Torres Strait Islander'},
                {code: 'CHCECE054-AT3A1', name: 'Research on supporting an Aboriginal and/or Torres Strait Islander'},
                {code: 'CHCECE054-AT3A2', name: 'collaborative ideas on support an Aboriginal and/or Torres Strait Islander'},
                {code: 'CHCECE054-AT3B', name: 'Examined different learning opportunities'},
                {code: 'CHCECE054-AT3C', name: 'Communicated learning opportunities to others'},
                {code: 'CHCECE054-AT3D', name: 'planned for the support of the group experience'},
                {code: 'CHCECE054-AT3E', name: 'Support an Aboriginal and/or Torres Strait Islander Cultures research and group discussion role play'},
                {code: 'CHCECE054-AT4', name: 'Supervisor feedback for the Activity performed with Torres Strait Islander'}
            ],
            
            'c3ecec': [
                {code: 'CHCECE037-AT1', name: 'Support children to connect with the natural environment'},
                {code: 'CHCECE037-AT2', name: 'Support Children\'s Knowledge and Understanding of the Natural Environment'},
                {code: 'CHCECE037-AT3', name: 'Outdoor and Indoor Learning Experiences'},
                {code: 'CHCECE037-AT4', name: 'Workplace Observation of Outdoor or Indoor Learning Experiences'},
                {code: 'CHCECE037-AT5', name: 'Supervisor Report about supporting in natural environment'},
                {code: 'CHCECE030&CHCECE054-AT1', name: 'Condition of Inclusion and Diversity'},
                {code: 'CHCECE030&CHCECE054-AT2', name: 'Critical Reflection on inclusion & diversity'},
                {code: 'CHCECE030&CHCECE054-AT3', name: 'Support Inclusion and Diversity in Daily Practice'},
                {code: 'CHCECE030&CHCECE054-AT4', name: 'Different approaches towards working with diversify groups'},
                {code: 'CHCECE030&CHCECE054-AT4D', name: 'Undertake a Group Experience of different culture'},
                {code: 'CHCECE030&CHCECE054-AT5', name: 'Supervisor Report on diversify culture'},
                {code: 'CHCECE033-AT1', name: 'Developing Positive and Respectful Relationships with Children'},
                {code: 'CHCECE033-AT2', name: 'Role play to build a positive children Kazim and Alana'},
                {code: 'CHCECE033-AT3', name: 'Communicating Positively and Respectfully With Children'},
                {code: 'CHCECE033-AT4', name: 'Relationships With Children'},
                {code: 'CHCECE033-AT5', name: 'Supervisor Report on build relation with Children'},
                {code: 'CHCECE055&CHCECE056-AT1', name: 'Work According to Legal and Ethical Obligations'},
                {code: 'CHCECE055&CHCECE056-AT2', name: 'Ethical and Legal Obligations comes in the Early child care'},
                {code: 'CHCECE055&CHCECE056-AT3A', name: 'Legal and Ethical Obligations Relating to Contemporary Educators'},
                {code: 'CHCECE055&CHCECE056-AT3B', name: 'Complete Work Activities as per Legal and Ethical Obligations'},
                {code: 'CHCECE055&CHCECE056-AT3C', name: 'Consult on Work Activities'},
                {code: 'CHCECE055&CHCECE056-AT4', name: 'Contribute to Improved Practices'},
                {code: 'CHCECE055&CHCECE056-AT5', name: 'Complete Work Activities in Line with Philosophy'},
                {code: 'CHCECE055&CHCECE056-AT6', name: 'Authenticated Third-Party Report on Working in a Early child care center'},
                {code: 'CHCPRT001-AT1', name: 'Written Questions'},
                {code: 'CHCPRT001-AT2', name: 'Identify and respond to children and young people at risk of abuse'},
                {code: 'CHCPRT001-AT3A', name: 'Disclosure of Abuse from Justin'},
                {code: 'CHCPRT001-AT3B', name: 'Report to Supervisor'},
                {code: 'CHCPRT001-AT4A', name: 'Report Supervisor and Director'},
                {code: 'CHCPRT001-AT4B', name: 'Role play on Reporting Suspicion of Child Abuse'},
                {code: 'CHCPRT001-AT5', name: 'Portfolio of Procedures and Experiences related to controlling of abuse cases'},
                {code: 'CHCECE034&CHCECE035&CHCECE036&CHCECE038-AT1', name: 'Supporting Children\'s Development and Growth'},
                {code: 'CHCECE034&CHCECE035&CHCECE036&CHCECE038-AT2', name: 'Different approaches towards Development and growth in Earlychildhood (A,B,C,E,F)'},
                {code: 'CHCECE034&CHCECE035&CHCECE036&CHCECE038-AT2D', name: 'Implement Experiences of Different approaches of Development'},
                {code: 'CHCECE034&CHCECE035&CHCECE036&CHCECE038-AT3', name: 'Planning and engaging of a Child with Different approaches towards development'},
                {code: 'CHCECE034&CHCECE035&CHCECE036&CHCECE038-AT4', name: 'Reflective Journal about the effectiveness of the methods about growth and development in Early Childhood'},
                {code: 'CHCECE034&CHCECE035&CHCECE036&CHCECE038-AT5', name: 'Induction guidance for a new joinee'},
                {code: 'HLTAID012-AT1', name: 'Providing First Aid in an Education and Care Setting'},
                {code: 'CHCECE031&CHCECE032-AT1', name: 'Caring a Child in Early Childhood'},
                {code: 'CHCECE031&CHCECE032-AT2', name: 'Critical Reflection on Relationships of Early Childhood'},
                {code: 'CHCECE031&CHCECE032-AT3', name: 'Children\'s Health and Safety'},
                {code: 'CHCECE031&CHCECE032-AT4', name: 'Showcase of how to Carry out baby care'},
                {code: 'CHCECE031&CHCECE032-AT5', name: 'Showcase of how to deal a toddler child'},
                {code: 'CHCECE031&CHCECE032-AT6', name: 'Reflect on Care Practice at Child care centers'},
                {code: 'CHCECE031&CHCECE032-AT7', name: 'Supervisor Report on caring a Child in Early Childhood'},
                {code: 'CHCDIV003-AT1', name: 'Working with children from different Cultures'},
                {code: 'CHCDIV003-AT2', name: 'Improving Workplace Diversity Practices'},
                {code: 'CHCDIV003-AT3', name: 'Analyse Workplace Diversity Practices and Plan Improvements'},
                {code: 'CHCDIV003-AT4', name: 'Supervisor Report on Working with diverse group of Children'},
                {code: 'HLTFSE001-AT1', name: 'Follow Basic Food Safety Practices'},
                {code: 'HLTFSE001-AT2', name: 'Hygiene and Food Safety Issues in the Kitchen'},
                {code: 'HLTFSE001-AT3', name: 'Implementation of different hygienic and food safety methods for early child care centers'},
                {code: 'HLTWHS001-AT1', name: 'Participate in workplace health and safety'},
                {code: 'HLTWHS001-AT2', name: 'Respond to Incidents & Emergencies'},
                {code: 'HLTWHS001-AT3', name: 'Assess Hazards and Risks in the Workplace'}
            ],
            
            'decec': [
                {code: 'BSBTWK502-AT1', name: 'Manage Team Effectiveness'},
                {code: 'BSBTWK502-AT2A', name: 'Organise a Team Meeting'},
                {code: 'BSBTWK502-AT2B', name: 'Role Play: Team Meeting'},
                {code: 'BSBTWK502-AT2C', name: 'Team Performance Review, Rewards and Recognition'},
                {code: 'BSBTWK502-AT3A', name: 'Performance Management (Observation)'},
                {code: 'BSBTWK502-AT3B', name: 'Policies and Procedures (Observation/Task)'},
                {code: 'CHCDIV003-AT1', name: 'Manage and Promote Diversity'},
                {code: 'CHCDIV003-AT2', name: 'Improving Workplace Diversity Practices (Role Play)'},
                {code: 'CHCDIV003-AT3', name: 'Work Placement Tasks'},
                {code: 'CHCECE041-AT1', name: 'Maintain a Safe and Healthy Environment for Children'},
                {code: 'CHCECE041-AT2', name: 'Compile Workplace Health and Safety Folder (Project)'},
                {code: 'CHCECE041-AT3', name: 'Design, Risk Assess and Participate in an Excursion (Project)'},
                {code: 'CHCECE041-AT4', name: 'Undertake Role of Workplace Health and Safety Officer (Case Study)'},
                {code: 'CHCECE050-AT1', name: 'Work in Partnership with Children\'s Families'},
                {code: 'CHCECE050-AT2', name: 'Providing Information to Families'},
                {code: 'CHCECE050-AT3A', name: 'Calling the Parents (Role Play)'},
                {code: 'CHCECE050-AT3B', name: 'Meeting the Parents (Role Play)'},
                {code: 'CHCECE050-AT4', name: 'Enrol and Support New Family (Role Play)'},
                {code: 'CHCECE050-AT5', name: 'Supporting Community Connections'},
                {code: 'CHCPOL002-AT1', name: 'Develop and Implement Policy'},
                {code: 'CHCPOL002-AT2A', name: 'Evaluate and Review Workplace Policies'},
                {code: 'CHCPOL002-AT2B', name: 'Develop and Implement Workplace Policies'},
                {code: 'CHCECE045-AT1', name: 'Behaviour and Inclusion'},
                {code: 'CHCECE045-AT2', name: 'Develop Guidelines to Promote Respectful Interactions and Inclusion'},
                {code: 'CHCECE045-AT3', name: 'Observe and Oversee Interactions and Behaviour in Children'},
                {code: 'CHCECE045-AT4', name: 'Identify Challenging Behaviours'},
                {code: 'CHCECE045-AT5', name: 'Develop, Implement and Evaluate Support Plans'},
                {code: 'CHCECE042-AT1', name: 'Written Questions - Foster holistic early childhood learning, development and wellbeing'},
                {code: 'CHCECE042-AT2', name: 'Developmental Assessment and Written Reflection'},
                {code: 'CHCECE042-AT3A', name: 'Planning Holistically for Children\'s Development'},
                {code: 'CHCECE042-AT3C', name: 'Implement Planned Learning Experience'},
                {code: 'CHCECE044-AT1', name: 'Compliance in Early Childhood'},
                {code: 'CHCECE044-AT2', name: 'Preparing the Service and Resolving Concerns'},
                {code: 'CHCECE044-AT3RP1', name: 'Responding to Systematic Problems to Improve Practice'},
                {code: 'CHCECE044-AT3RP2', name: 'Respond to a Complaint Effectively'},
                {code: 'CHCECE044-AT4', name: 'Plan for Environmental Responsibilities'},
                {code: 'CHCECE044-AT5', name: 'Facilitate Compliance in an Education and Care Setting'},
                {code: 'CHCECE043-AT1', name: 'Planning and Curriculum'},
                {code: 'CHCECE043-AT2', name: 'Develop a Focus Children Folder'},
                {code: 'CHCECE043-AT3A', name: 'Plan and Implement Curriculum to Nurture Creativity in Children'},
                {code: 'CHCECE043-AT3F', name: 'Workplace Observation'},
                {code: 'CHCECE043-AT4', name: 'Reflective Journal'},
                {code: 'CHCECE043-AT5', name: 'Supervisor Report'},
                {code: 'CHCPRP003-AT1', name: 'Reflect on and improve own professional practice'},
                {code: 'CHCPRP003-AT2', name: 'Practice Improvement Research Report – Sector Developments'},
                {code: 'CHCPRP003-AT3', name: 'Feedback to Improve Practice'},
                {code: 'CHCPRP003-AT4', name: 'Personal Development Plan'}
            ],
            
            'cs': [
                {code: 'HLTWHS004-AT1', name: 'Manage work health and safety'},
                {code: 'HLTWHS004-AT2', name: 'Case Studies for managing hazard situation'},
                {code: 'HLTWHS004-AT3', name: 'Project 1 - WHS Inspection methods'},
                {code: 'HLTWHS004-AT4', name: 'Project 2 - WHS Risk Assessment planning'},
                {code: 'HLTWHS004-AT5', name: 'Project 3 - Consult with Staff to act on the developed plan'},
                {code: 'HLTWHS004-AT6', name: 'Helping in controlling the hazard at Workplace'},
                {code: 'HLTWHS004-AT7', name: 'Verbal explaining the control measure to reduce the plan'},
                {code: 'CHCADV002-AT1', name: 'Provide advocacy and representation services'},
                {code: 'CHCADV002-AT2', name: 'Research Project to provide advocacy'},
                {code: 'CHCADV002-AT3A', name: 'Idea for the self advocacy - roleplay'},
                {code: 'CHCADV002-AT3B', name: 'Representing the Client - in legal support'},
                {code: 'CHCADV002-AT4', name: 'Showcase the advocacy for the client and provide the related support'},
                {code: 'CHCPRP003-AT1', name: 'Reflect on and improve own professional practice'},
                {code: 'CHCPRP003-AT2', name: 'Research on self improvement'},
                {code: 'CHCPRP003-AT3', name: 'Workplace Project – Seek and Share Feedback'},
                {code: 'CHCPRP003-AT4', name: 'Project – Personal Development Plan post workplace feedback'},
                {code: 'CHCCOM003-AT1', name: 'Develop workplace communication strategies'},
                {code: 'CHCCOM003-AT2', name: 'Project – Digital Media Strategy'},
                {code: 'CHCCOM003-AT3', name: 'Implement a Digital Media Strategy – Overview'},
                {code: 'CHCCOM003-AT3A', name: 'Email for discussing the Digital Media Strategy'},
                {code: 'CHCCOM003-AT3B', name: 'Coaching Session for the Digital Media Strategy'},
                {code: 'CHCCOM003-AT4', name: 'Workplace Project – Develop Communication Strategy'},
                {code: 'CHCCOM003-AT5A', name: 'Email Invitation'},
                {code: 'CHCCOM003-AT5B', name: 'Lead a Meeting to Present and Review the Strategy'},
                {code: 'CHCCOM003-AT5C', name: 'Evaluate the Strategy outcomes'},
                {code: 'CHCMGT005-AT1', name: 'Facilitate workplace debriefing and support processes'},
                {code: 'CHCMGT005-AT2A', name: 'Plan and Prepare for the Debriefing Session'},
                {code: 'CHCMGT005-AT2B', name: 'Conduct the Debriefing Sessions'},
                {code: 'CHCMGT005-AT3', name: 'Project to show the way of conducting a Debriefing section'},
                {code: 'CHCMGT005-AT4', name: 'Workplace Observation For the support section'},
                {code: 'CHCMGT005-AT5', name: 'Workplace Project in supporting person on the Workplace'},
                {code: 'CHCCSL001-AT1', name: 'Establish and confirm the counselling relationship'},
                {code: 'CHCCSL001-AT2', name: 'Research Project to client relation at Work place'},
                {code: 'CHCCSL001-AT3A', name: 'Role Play 1 – Jeff'},
                {code: 'CHCCSL001-AT3B', name: 'Role Play 2 – Sandra'},
                {code: 'CHCCSL001-AT3C', name: 'Role Play 3 – Georgina'},
                {code: 'CHCCSL001-AT4', name: 'Planning Project for providing counseling section to supportive persons'},
                {code: 'CHCCCS003-AT1', name: 'increase the safety of individuals at risk of suicide'},
                {code: 'CHCCCS003-AT2', name: 'Case Study for the self harm controlling and dealing'},
                {code: 'CHCCCS003-AT3A', name: 'Role Play 1 – Angelina'},
                {code: 'CHCCCS003-AT3B', name: 'Role Play 2 – Dane'},
                {code: 'CHCCCS003-AT3C', name: 'Role Play 3 – Adisa'},
                {code: 'CHCCCS003-AT4', name: 'Client Reports for Workplace support'},
                {code: 'CHCCCS003-AT5', name: 'Supervisor Report for feedback'},
                {code: 'CHCDIV003-AT1', name: 'Manage and promote diversity'},
                {code: 'CHCDIV003-AT2', name: 'Case Study for support person from different culture groups'},
                {code: 'CHCDIV003-AT3', name: 'Role Play: Working relation with different culture persons'},
                {code: 'CHCDIV003-AT4', name: 'Workplace Project: related to different culture person encounters and supporting'},
                {code: 'CHCDIV003-AT5', name: 'Presentation to show the basics for the working with multi-culture Workplace'},
                {code: 'CHCLEG003-AT1', name: 'Manage legal and ethical compliance'},
                {code: 'CHCLEG003-AT2', name: 'Case Studies for overview the legal and ethical approach'},
                {code: 'CHCLEG003-AT3', name: 'Project in dealing matters within legal and ethical rights of the clients'},
                {code: 'CHCCCS007-AT1', name: 'Developing Service Programs'},
                {code: 'CHCCCS007-AT2', name: 'Social and Cultural Issues within Australia'},
                {code: 'CHCCCS007-AT3', name: 'Assess Issues and Determine a Plan with a Client – Roleplay'},
                {code: 'CHCCCS007-AT4', name: 'Develop, Implement and Evaluate a Service Program'},
                {code: 'CHCCCS007-AT5', name: 'Analyse Impacts of Services'},
                {code: 'CHCCCS009-AT1', name: 'Facilitate responsible behaviour'},
                {code: 'CHCCCS009-AT2', name: 'Case Study to reflect the behavioural responsibilities towards client'},
                {code: 'CHCCCS009-AT3', name: 'Project and Roleplays about the facility policies and procedures'},
                {code: 'CHCCCS019-AT1', name: 'Recognise and respond to crisis situations'},
                {code: 'CHCCCS019-AT2', name: 'Recognise and Respond to Crisis – Denise - Roleplay'},
                {code: 'CHCCCS019-AT3', name: 'Recognise and Respond to Crisis – Serena - Roleplay'},
                {code: 'CHCCCS019-AT4A', name: 'Respond to an Initial Crisis - Roleplay'},
                {code: 'CHCCCS019-AT4B', name: 'Follow-up with Colman - Roleplay'},
                {code: 'CHCDIV002-AT1', name: 'Promote Aboriginal and/or Torres Strait Islander cultural safety'},
                {code: 'CHCDIV002-AT2', name: 'Intergenerational Trauma'},
                {code: 'CHCDIV002-AT3', name: 'Cultural Safety Needs and Strategies'},
                {code: 'CHCDIV002-AT4', name: 'Reflecting on the Implementation of Cultural Safety'},
                {code: 'CHCDIV002-AT5', name: 'Supervisor Report for feedback about cultural safety'},
                {code: 'CHCCSM013-AT1', name: 'Facilitate and review case management'},
                {code: 'CHCCSM013-AT2', name: 'Contemporary Behaviour Change'},
                {code: 'CHCCSM013-AT3A', name: 'Scenario Client in needs with the disabilities and required the help'},
                {code: 'CHCCSM013-AT3C', name: 'Case Management Meeting - Roleplay'},
                {code: 'CHCCSM013-AT4', name: 'Workplace project to overview: Facilitate and review case management'},
                {code: 'CHCCSM013-AT5', name: 'Supervisor Report: Facilitate and review case management'},
                {code: 'CHCCCS004-AT1', name: 'Assess co-existing needs'},
                {code: 'CHCCCS004-AT2A', name: 'Prepare to Undertake Assessment: Assess a Person\'s Co-existing Needs – Joanne'},
                {code: 'CHCCCS004-AT2B', name: 'Assess Client Needs Using Collaborative Approach (Role Play)'},
                {code: 'CHCCCS004-AT2C', name: 'documentation of the procedures for joanna'},
                {code: 'CHCCCS004-AT3A', name: 'Prepare to Undertake Assessment'},
                {code: 'CHCCCS004-AT3B', name: 'Assess Client Needs Using Collaborative Approach (Role Play)'},
                {code: 'CHCCCS004-AT3C', name: 'Assess a Person\'s Co-existing Needs – Sonny'},
                {code: 'CHCCCS004-AT4A', name: 'Prepare to Undertake Assessment'},
                {code: 'CHCCCS004-AT4B', name: 'Assess Client Needs Using Collaborative Approach (Role Play)'},
                {code: 'CHCCCS004-AT4C', name: 'Assess a Person\'s Co-existing Needs – Boran'},
                {code: 'CHCCCS004-AT5', name: 'Reflect on Feedback from the role play performed'},
                {code: 'CHCDFV001-AT1', name: 'Recognise and respond appropriately to domestic and family violence'},
                {code: 'CHCDFV001-AT2', name: 'Context of Domestic Violence and its Impacts'},
                {code: 'CHCDFV001-AT3', name: 'Supporting Dianne – Roleplay'},
                {code: 'CHCDFV001-AT4', name: 'Supporting Priyanka – Roleplay'},
                {code: 'CHCDFV001-AT5', name: 'Supporting Oliver – Roleplay'},
                {code: 'CHCDIV001-AT1', name: 'Work with diverse people'},
                {code: 'CHCDIV001-AT2', name: 'Cultural Diversity in Australia'},
                {code: 'CHCDIV001-AT3', name: 'Communicate with Culturally Diverse People'},
                {code: 'CHCDIV001-AT4', name: 'Reflect on Own Cultural Competency in the Workplace'},
                {code: 'HLTWHS003-AT1', name: 'Maintain work health and safety'},
                {code: 'HLTWHS003-AT2A', name: 'Risk Assessment and Control Strategies Part A & B'},
                {code: 'HLTWHS003-AT2C', name: 'Risk Assessment and Control Strategies Part C (Observation)'},
                {code: 'HLTWHS003-AT3', name: 'Emergency Procedure and Incident Reporting (Roleplay)'},
                {code: 'CHCCSM014-AT1', name: 'Provide case management supervision'},
                {code: 'CHCCSM014-AT2', name: 'Practice Standard for Case Workers'},
                {code: 'CHCCSM014-AT3A', name: 'Initial Supervision Meeting'},
                {code: 'CHCCSM014-AT3B', name: 'Second supervision meeting'},
                {code: 'CHCCSM014-AT3C', name: 'referral to another service'},
                {code: 'CHCCSM014-AT3D', name: 'supervision evaluation session'},
                {code: 'CHCCSM014-AT3E', name: 'refer issues beyond scope of practice'}
            ],
            
            'aging-old': [
                {code: 'CHCDIS007-AT1', name: 'Facilitate the Empowerment of People with Disability'},
                {code: 'CHCDIS007-AT2', name: 'Working and identification help to disable person'},
                {code: 'CHCDIS007-AT3', name: 'Project Assessment for legal and ethical approach for Disable person'},
                {code: 'CHCDIS007-AT4', name: 'Case Studies helping a person with disability'},
                {code: 'CHCDIS007-ATSW', name: 'facilitate the empowerment of people with disability'},
                {code: 'CHCCCS025-AT1', name: 'Support relationships with carers and families'},
                {code: 'CHCCCS025-AT2', name: 'Carers and families role for the aging person'},
                {code: 'CHCCCS025-AT3', name: 'providing help to aged person'},
                {code: 'CHCCCS025-ATSW', name: 'Home and community support guidelines'},
                {code: 'CHCPRP001-AT1', name: 'Develop and maintain networks and collaborative partnerships'},
                {code: 'CHCPRP001-AT2', name: 'Facilitation Techniques for Disability Empowerment'},
                {code: 'CHCPRP001-AT3', name: 'Strategies to Facilitate Empowerment among People with Disabilities'},
                {code: 'CHCPRP001-AT4', name: 'Case Study: Empowering People with Disabilities'},
                {code: 'CHCPRP001-ATSW', name: 'develop and maintain networks and collaborative partnerships'},
                {code: 'CHCCCS023-AT1', name: 'Recognise healthy body systems'},
                {code: 'CHCCCS023-AT2', name: 'individual support with wellbeing and body health'},
                {code: 'CHCCCS023-AT3', name: 'Care plan and helping in follow the plan'},
                {code: 'CHCCCS023-ATSW', name: 'support independence and wellbeing & recognise healthy body systems'},
                {code: 'CHCLEG003-AT1', name: 'Understanding the legal and ethical responsibilities'},
                {code: 'CHCLEG003-AT2', name: 'knowledge of legal frameworks, ethical principles, and safety procedures'},
                {code: 'CHCLEG003-AT3', name: 'Case Studies Applying legal, ethical, and safety principles in care scenario'},
                {code: 'CHCLEG003-AT4', name: 'idea of dealing real-life care scenario to ensure best practice'},
                {code: 'CHCLEG003-ATSW', name: 'work in health and community sector'},
                {code: 'CHCCOM005-AT1', name: 'Building positive relationships with clients and colleagues'},
                {code: 'CHCCOM005-AT2', name: 'Verbal and non-verbal communication techniques'},
                {code: 'CHCCOM005-AT3', name: 'Supporting a person from a culturally diverse or marginalised group'},
                {code: 'CHCCOM005-ATSW', name: 'Handling a misunderstanding caused by cultural differences in communication'},
                {code: 'CHCCCS011-AT1', name: 'Supporting physical, emotional, and social needs of clients'},
                {code: 'CHCCCS011-AT2', name: 'Safe manual handling, hygiene, and infection control procedures'},
                {code: 'CHCCCS011-AT3', name: 'Assisting an older client with daily activities while encouraging independence'},
                {code: 'CHCCCS011-ATSW', name: 'support and empowerment of older people'},
                {code: 'CHCPAL001-AT1', name: 'Supporting physical, emotional, social, and spiritual needs'},
                {code: 'CHCPAL001-AT2', name: 'Legal and ethical responsibilities in end-of-life care'},
                {code: 'CHCPAL001-AT3', name: 'Assisting a client to maintain dignity and comfort during end-of-life care'},
                {code: 'CHCPAL001-AT4', name: 'Role Play for Supporting family members during the clients care journey'},
                {code: 'CHCPAL001-ATSW', name: 'deliver care services using a palliative approach'},
                {code: 'HLTHPS006NEW-AT1', name: 'Correct procedures for administering or assisting with medication'},
                {code: 'HLTHPS006NEW-AT2', name: 'Communicating with healthcare professionals regarding medication concerns'},
                {code: 'HLTHPS006NEW-AT3', name: 'Ensuring accurate documentation of medication administration'},
                {code: 'HLTHPS006NEW-AT4', name: 'Reporting errors or unusual client reactions'},
                {code: 'CHCADV001-AT1', name: 'Developing and implementing person-centred service plans'},
                {code: 'CHCADV001-AT2', name: 'Developing and implementing a personalised care plan'},
                {code: 'CHCADV001-ATSW', name: 'Creating a care or support plan for a client with specific needs'},
                {code: 'HLTAID003-AT1', name: 'Recognising and assessing emergency situations'},
                {code: 'HLTAID003-AT2', name: 'Understanding legal and workplace responsibilities in first aid'},
                {code: 'HLTHPS006OLD-AT1', name: 'Correct procedures for administering or assisting with medication'},
                {code: 'HLTHPS006OLD-AT2', name: 'Communicating with healthcare professionals regarding medication concerns'},
                {code: 'HLTHPS006OLD-AT3', name: 'Ensuring accurate documentation of medication administration'},
                {code: 'HLTHPS006OLD-AT4', name: 'Reporting errors or unusual client reactions'}
            ],
            
            'aging-new': [
                { code: 'CHCDIV001-T4', name: 'Reflection on Cultural diversity in the Workplace' },
                { code: 'CHCDIS007-AT4', name: 'Performing interviews and gathering information about clients' },
                { code: 'CHCCCS025-AT3', name: 'Discussing the strength-based solutions for the clients' },
                { code: 'CHCCCS025-AT4', name: 'Implementing different strategies for the clients with co-workers' },
                { code: 'CHCPRP001-AT2', name: 'Research on the policies & procedures of the workplace' },
                { code: 'CHCPRP001-AT3', name: 'Journals for experience in collaboration with co-workers & clients' },
                { code: 'HLTAAP001-T4', name: 'Identifying & gathering information about the physical health of the clients' },
                { code: 'CHCLEG003-AT3', name: 'Equal opportunity in workplace with all legal & ethical rights' },
                { code: 'HLTWHS002-T3', name: 'Inspection checklist for hazard safety for workplace' },
                { code: 'HLTWHS002-AT4', name: 'Risk assessment for workplace hazards and safety policies' },
                { code: 'CHCAGE001-AT5', name: 'Ways to empower older people in achieving goals & aspirations' },
                { code: 'CHCAGE001-AT6', name: 'Supervisor reports in empowering aged people towards their goals' },
                { code: 'CHCAGE003-AT4', name: 'Providing and coordinating services for aged people' },
                { code: 'CHCAGE003-AT5', name: 'Providing & obtaining feedback for services provided to clients and caregivers' },
                { code: 'CHCAGE004-AT3', name: 'Portfolio for implementation of strategies for aged people' },
                { code: 'CHCCCS023-AT4', name: 'Assisting clients in daily activities' },
                { code: 'CHCPRP001-AT4', name: 'Feedback forms for services provided' },
                { code: 'HLTWHS002-T5', name: 'Implementing policies for handling emergency situations' },
                { code: 'CHCCCS011-AT3', name: 'Handling a person in & out of the vehicle' },
                { code: 'CHCCCS011-AT4', name: 'Supporting clients with personal care needs' },
                { code: 'CHCAGE005-AT6', name: 'Working with clients with dementia and supporting them in personal care' },
                { code: 'CHCDIV001-AT1', name: 'Working with diverse people from different backgrounds' },
                { code: 'CHCDIV001-AT2', name: 'Research on diversity in Australia' },
                { code: 'CHCDIV001-AT3', name: 'Roleplay of communicating with culturally different people' },
                { code: 'CHCDIS007-AT1', name: 'Facilitating empowerment of people with disabilities' },
                { code: 'CHCDIS007-AT2', name: 'Case studies for empowering people with disabilities' },
                { code: 'CHCDIS007-AT3', name: 'Research on different disabilities & empowerment techniques' },
                { code: 'CHCCOM005-AT1', name: 'Initiating ideas about communicating & working in health & community services' },
                { code: 'CHCCOM005-AT2', name: 'Case studies for communicating & working in health & community services' },
                { code: 'CHCCOM005-AT3', name: 'Communicating with different clients' },
                { code: 'CHCCOM005-AT4', name: 'Communicating with different co-workers' },
                { code: 'CHCCOM005-AT5', name: 'Communicating with different coordinators' },
                { code: 'CHCCCS025-AT1', name: 'Supporting clients relationships with family members & caregivers' },
                { code: 'CHCCCS025-AT2', name: 'Case studies in supporting clients relationships with caregivers' },
                { code: 'CHCPRP001-AT1', name: 'Collaboration & feedback in aged care services' },
                { code: 'CHCCCS023-AT1', name: 'Supporting independence and wellbeing of clients' },
                { code: 'CHCCCS023-AT2', name: 'Case studies on supporting independence and wellbeing of clients' },
                { code: 'CHCCCS023-AT3', name: 'Roleplay on supporting & wellbeing techniques for aged clients' },
                { code: 'HLTAAP001-AT1', name: 'Recognizing needs to improve physical health of clients' },
                { code: 'HLTAAP001-AT2', name: 'Case studies to improve physical health of aged clients' },
                { code: 'HLTAAP001-AT3', name: 'Ways to gather information about physical health needs of clients' },
                { code: 'CHCLEG003-AT1', name: 'Recognizing legal & ethical rights for clients in aged care' },
                { code: 'CHCLEG003-AT2', name: 'Case study for providing legal & ethical support to clients' },
                { code: 'CHCLEG003-AT4', name: 'Project on providing and supporting legal & ethical care for clients' },
                { code: 'HLTWHS002-AT1', name: 'Following safety policies and practices in aged care' },
                { code: 'HLTWHS002-AT2', name: 'Case study on safety protocols for different client conditions' },
                { code: 'CHCCCS011-AT1', name: 'Assisting clients in meeting their personal needs' },
                { code: 'CHCCCS011-AT2', name: 'Case study on providing support for meeting personal needs' },
                { code: 'CHCAGE001-AT1', name: 'Facilitating older people for self-empowerment' },
                { code: 'CHCAGE001-AT2', name: 'Case studies for empowering older people for self-improvement' },
                { code: 'CHCAGE001-AT3', name: 'Roleplay on supporting & empowerment techniques for aged people' },
                { code: 'CHCAGE001-AT4', name: 'Project assisting clients for empowerment in daily chores' },
                { code: 'CHCAGE005-AT1', name: 'Providing support to people with dementia' },
                { code: 'CHCAGE005-AT2', name: 'Case studies on assisting people with dementia' },
                { code: 'CHCAGE005-AT3', name: 'Roleplay in helping people with dementia and improving conditions' },
                { code: 'CHCAGE005-AT4', name: 'Assessing behaviours and implementing review plans for dementia clients' },
                { code: 'CHCAGE005-AT5', name: 'Gathering information about different conditions of dementia' },
                { code: 'CHCAGE003-AT1', name: 'Different ways of coordinating with older people' },
                { code: 'CHCAGE003-AT2', name: 'Case study about coordinating process with older people' },
                { code: 'CHCAGE003-AT3', name: 'Roleplay on coordinating improvement techniques with family members' },
                { code: 'CHCAGE004-AT1', name: 'Implementing ideas & ways to assist older people at risk' },
                { code: 'CHCAGE004-AT2', name: 'Case study on helping clients at risk in older age' },
                { code: 'CHCCCS006-AT1', name: 'Facilitating individuals with planning and implementation' },
                { code: 'CHCCCS006-AT2', name: 'Home care planning and implementation with Allan' },
                { code: 'CHCCCS006-AT3', name: 'Communicating and coordinating support for Salwa' },
                { code: 'CHCCCS006-AT4', name: 'Identifying service improvement areas for Rafaels' },
                { code: 'CHCADV001-AT1', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCADV001-AT2', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCADV001-AT3', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCADV001-AT4', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCADV001-AT5', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCPAL001-AT1', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCPAL001-AT2', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCPAL001-AT3', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCPAL001-AT4', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCPAL001-AT5', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCAGE013-AT1', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCAGE013-AT2', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCAGE013-AT3', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCAGE013-AT4', name: 'No task comments – file unavailable on New LMS' },
                { code: 'CHCAGE013-AT5', name: 'No task comments – file unavailable on New LMS' }
            ],
            
            'cis': [
                {code: 'CHCDIS012-AT1', name: 'Support community participation and social inclusion'},
                {code: 'CHCDIS012-AT2', name: 'Support to Access Community or Social Opportunities'},
                {code: 'CHCDIS012-AT2A', name: 'Client Requiring Support (Role Play)'},
                {code: 'CHCDIS012-AT2B', name: 'Develop a Community Support Plan & Contact Community Provider'},
                {code: 'CHCDIS012-AT3', name: 'Support to Access Community or Volunteer Work Opportunities'},
                {code: 'CHCDIS012-AT3A', name: 'Client Requiring Work Support (Role Play)'},
                {code: 'CHCDIS012-AT3B', name: 'Develop a Workplace Participation Plan & Contact Workplace Provider'},
                {code: 'CHCDIS012-AT4', name: 'Monitor and Review'},
                {code: 'CHCDIS012-AT4A', name: 'Follow-Up With Naomi (Role Play)'},
                {code: 'CHCDIS012-AT4B', name: 'Follow-Up With Donny (Role Play)'},
                {code: 'CHCDIS012-AT4C', name: 'Contact Providers'},
                {code: 'CHCDIS011-AT1', name: 'Knowledge Questions'},
                {code: 'CHCDIS011-AT2', name: 'Case Studies'},
                {code: 'CHCDIS011-AT3A', name: 'Review the Individual Action Plan for Your Client'},
                {code: 'CHCDIS011-AT3B', name: 'Support Skills Development (Role Play)'},
                {code: 'CHCDIS011-AT3C', name: 'Complete and Distribute Documentation'},
                {code: 'CHCDIS011-AT3D', name: 'Implement Skills Development (Role Play)'},
                {code: 'CHCDIS011-AT3E', name: 'Maintain Client Documentation'},
                {code: 'CHCDIS011-AT4A', name: 'Contributing to Skills Development – Trudy'},
                {code: 'CHCDIS011-AT4B', name: 'Plan Skills Development (Role Play)'},
                {code: 'CHCDIS011-AT4C', name: 'Complete and Distribute Documentation'},
                {code: 'CHCDIS011-AT4D', name: 'Implement Skills Development (Role Play)'},
                {code: 'CHCDIS011-AT4E', name: 'Maintain Client Documentation'},
                {code: 'CHCDIS011-AT5A', name: 'Skills Assessment to work with disabilities'},
                {code: 'CHCDIS011-AT5B', name: 'Skills Development (Observation)'},
                {code: 'CHCDIV001-AT1', name: 'Work with Diverse People'},
                {code: 'CHCDIV001-AT2', name: 'Cultural Diversity in Australia'},
                {code: 'CHCDIV001-AT3', name: 'Communicate with Culturally Diverse People (Role Play)'},
                {code: 'CHCDIV001-AT4', name: 'Reflect on Own Cultural Competency in the Workplace'},
                {code: 'CHCLEG001-AT1', name: 'Work legally and ethically'},
                {code: 'CHCLEG001-AT2', name: 'Case Studies for Work legally and ethically'},
                {code: 'CHCLEG001-AT3', name: 'Contribute to Workplace Improvements'},
                {code: 'CHCLEG001-AT3A', name: 'Identify Workplace Improvements'},
                {code: 'CHCLEG001-AT3B', name: 'Discuss Workplace Improvements (Role Play)'},
                {code: 'CHCLEG001-AT4', name: 'Legal and Ethical Responsibilities at Banksia Care'},
                {code: 'CHCLEG001-AT4A', name: 'legal and ethical rights For Hannah Pearce'},
                {code: 'CHCLEG001-AT4B', name: 'legal and ethical rights For Harry Jenkins'},
                {code: 'CHCCOM005-AT1', name: 'Communicate and work in health or community services'},
                {code: 'CHCCOM005-AT2', name: 'Case Studies'},
                {code: 'CHCCOM005-AT3A', name: 'Communicate with a Client'},
                {code: 'CHCCOM005-AT3B', name: 'Email Coordinator'},
                {code: 'CHCCOM005-AT4A', name: 'Communicate with Co-worker'},
                {code: 'CHCCOM005-AT4B', name: 'Email Coordinator'},
                {code: 'CHCCOM005-AT5A', name: 'Meeting with Coordinator'},
                {code: 'CHCCOM005-AT5B', name: 'Complete Documentation'},
                {code: 'HLTINF006-AT1', name: 'Work Safely in Client Care'},
                {code: 'HLTINF006-AT2', name: 'Case Studies'},
                {code: 'HLTINF006-AT3', name: 'Mark – Cleaning up Blood or Body Fluids'},
                {code: 'HLTINF006-AT4', name: 'Assisting a Client in a Wheelchair Exit a Building'},
                {code: 'HLTINF006-AT5', name: 'Eldred – Cleaning up Blood or Body Fluids'},
                {code: 'HLTINF006-AT6', name: 'Participating in a WHS Meeting'},
                {code: 'HLTINF006-AT7', name: 'Brianna – Client Contracts Infectious Disease'},
                {code: 'CHCCCS041-AT1', name: 'Recognise healthy body systems'},
                {code: 'CHCCCS041-AT2', name: 'Assist a Client with their Health Concerns'},
                {code: 'CHCCCS041-AT3', name: 'Assist a Client to Attend Weekly Sport'},
                {code: 'CHCCCS041-AT4', name: 'Assist a Client During Scheduled Health Check'},
                {code: 'CHCAGE013-AT1', name: 'Work effectively in aged care'},
                {code: 'CHCAGE013-AT2', name: 'Day in the Life of a Personal Care Worker'},
                {code: 'CHCAGE013-AT2A', name: 'Day in the Life of a Personal Care Worker; Position Description'},
                {code: 'CHCAGE013-AT2B', name: 'Day in the Life of a Personal Care Worker; Providing Care'},
                {code: 'CHCAGE013-AT2C', name: 'Completing Reports'},
                {code: 'CHCMHS001-AT1', name: 'Work with people with mental health issues'},
                {code: 'CHCMHS001-AT2', name: 'Research Report'},
                {code: 'CHCMHS001-AT3', name: 'Working with a Client with Depression'},
                {code: 'CHCMHS001-AT4', name: 'Working with a Client with Post-Concussion Syndrome'},
                {code: 'CHCMHS001-AT5', name: 'Working with a Client with Post-Traumatic Stress Disorder'},
                {code: 'CHCAGE011-AT1', name: 'Provide support to people living with dementia'},
                {code: 'CHCAGE011-AT2', name: 'Assist Edna'},
                {code: 'CHCAGE011-AT3', name: 'Recognise Signs of Abuse'},
                {code: 'CHCAGE011-AT4', name: 'Support Clients with Dementia'},
                {code: 'CHCAGE011-AT5', name: 'Client Work Reports'},
                {code: 'CHCCCS031-AT1', name: 'Provide individualised support'},
                {code: 'CHCCCS031-AT2', name: 'Case Studies'},
                {code: 'CHCCCS031-AT3A', name: 'First Client Simulation – Suzanne'},
                {code: 'CHCCCS031-AT3B', name: 'Second Client Simulation – Samuel'},
                {code: 'CHCCCS031-AT3C', name: 'Third Client Simulation – Chandra'},
                {code: 'CHCCCS031-AT4A', name: 'Workplace Observation | 1st Visit'},
                {code: 'CHCCCS031-AT4B', name: 'Workplace Observation | 2nd Visit'},
                {code: 'CHCCCS031-AT4C', name: 'Workplace Observation | 3rd Visit'},
                {code: 'CHCCCS038-AT1', name: 'Wellbeing, Independence and Empowerment'},
                {code: 'CHCCCS038-AT2', name: 'Case Study'},
                {code: 'CHCCCS038-AT3', name: 'Individual Differences'},
                {code: 'CHCCCS038-AT4A', name: 'Client Interview'},
                {code: 'CHCCCS038-AT4B', name: 'Support Plan and Report'},
                {code: 'CHCCCS038-AT5A', name: 'Supporting Clients'},
                {code: 'CHCCCS038-AT5B', name: 'Reporting Client Incident Situations'},
                {code: 'CHCCCS038-AT5C', name: 'Reporting Client Situations of Abuse'},
                {code: 'CHCCCS038-AT6', name: 'Supervisor Report'}
            ]
        };

        // Qualification selection
        

        function selectQualification(qualCode, qualName, element) {
            document.querySelectorAll('.qualification-item').forEach(item => {
                item.classList.remove('active');
            });
            element.classList.add('active');
            document.getElementById('activeQual').textContent = qualName;
            currentQual = qualCode;
            populateTaskDropdown(qualCode);
        }

        function populateTaskDropdown(qualCode) {
            const taskSelect = document.getElementById('taskSelect');
            taskSelect.innerHTML = '<option value="">Select an assessment task...</option>';
            const tasks = allTasks[qualCode] || [];
            
            tasks.forEach(task => {
                const option = document.createElement('option');
                option.value = task.name;
                option.textContent = `${task.code} - ${task.name}`;
                taskSelect.appendChild(option);
            });
        }

        populateTaskDropdown('c4es');

        const commentsByTone = {
            'short': [
                'Hi {name}, your {task} work is satisfactory and meets requirements. Keep up the consistent effort in future assessments.',
                'Hi {name}, {task} demonstrates satisfactory completion. Continue applying what you have learned in upcoming tasks.',
                'Hi {name}, your {task} submission is satisfactory. You are on track with your learning progress.',
                'Hi {name}, satisfactory work on {task}. Maintain this standard as you move forward in the course.',
                'Hi {name}, your {task} is satisfactory. Continue working at this level in your future assessments.',
                'Hi {name}, {task} meets the required standard. Keep building on what you have achieved so far.',
                'Hi {name}, your {task} work is satisfactory. You are progressing well through the unit requirements.',
                'Hi {name}, satisfactory outcome for {task}. Continue demonstrating this level of competence in your work.',
                'Hi {name}, your {task} is satisfactory and shows good foundational understanding. Keep up the effort.',
                'Hi {name}, {task} completed satisfactorily. You are meeting expectations and developing well in this area.'
            ],
            'encouraging': [
                'Hi {name}, your work on {task} is satisfactory and shows real progress! You are building confidence and doing great—keep it up.',
                'Hi {name}, well done on {task}—this is satisfactory work and you should feel proud! You are developing important skills and moving forward nicely.',
                'Hi {name}, fantastic effort on {task}! Your satisfactory work shows dedication and you are clearly growing in your professional abilities.',
                'Hi {name}, great job with {task}—your satisfactory performance reflects genuine commitment! You are on a positive path forward.',
                'Hi {name}, excellent work on {task}! You have achieved a satisfactory standard and are showing wonderful improvement in your capabilities.',
                'Hi {name}, well done! Your {task} is satisfactory and demonstrates that your hard work is really paying off nicely.',
                'Hi {name}, your {task} work is satisfactory and truly commendable! You are developing skills with energy and enthusiasm—keep going!',
                'Hi {name}, congratulations on {task}! Your satisfactory achievement shows you are applying yourself well and making great strides forward.',
                'Hi {name}, impressive effort on {task}! You have met the satisfactory standard and your progress is evident and encouraging.',
                'Hi {name}, you should be pleased with your {task} work—it is satisfactory and reflects positive growth! Keep up the momentum.'
            ],
            'detailed': [
                'Hi {name}, your work on {task} is satisfactory and demonstrates developing competence in key areas including task completion, attention to instructions, and awareness of workplace expectations. You are showing steady improvement in your ability to apply learning in practical contexts.',
                'Hi {name}, your {task} submission is satisfactory and reflects consistent effort across multiple competencies such as communication, teamwork, and procedural understanding. You have met the required benchmarks for this stage and are building a solid foundation.',
                'Hi {name}, your {task} work is satisfactory and shows appropriate engagement with the assessment criteria, including understanding of concepts, application of knowledge, and adherence to submission guidelines. You are progressing satisfactorily through the learning outcomes.',
                'Hi {name}, your {task} outcome is satisfactory and demonstrates that you have addressed the core requirements effectively, including task analysis, procedural accuracy, and professional presentation. You are developing competence in these areas.',
                'Hi {name}, your {task} is satisfactory and indicates that you have understood the key learning objectives, applied relevant skills appropriately, and met the expected standards. You are building knowledge systematically.',
                'Hi {name}, your {task} submission is satisfactory and shows competence in several areas including problem identification, appropriate responses, and documentation quality. You are meeting the unit requirements satisfactorily.',
                'Hi {name}, your {task} work is satisfactory and reflects your ability to understand instructions, carry out tasks methodically, and present work professionally. You are developing these capabilities steadily.',
                'Hi {name}, your {task} is satisfactory and demonstrates your developing skills in workplace practices, task management, and communication. You have addressed the assessment criteria appropriately.',
                'Hi {name}, your {task} submission is satisfactory and shows that you have engaged with the learning content, applied it to practical scenarios, and produced work that meets the required standard.',
                'Hi {name}, your {task} outcome is satisfactory and indicates competence in understanding key concepts, following procedures correctly, and presenting information clearly. You are progressing well through this unit.'
            ],
            'growth': [
                'Hi {name}, your {task} work is satisfactory and shows that you are developing important workplace skills. As you continue, focus on strengthening your confidence and refining your approach.',
                'Hi {name}, your {task} submission is satisfactory and reflects your learning journey so far. Keep building on this foundation—you are making progress with clear opportunities to grow.',
                'Hi {name}, your {task} is satisfactory and demonstrates emerging competence. You are developing skills steadily and have room to deepen your understanding in future tasks.',
                'Hi {name}, your {task} work is satisfactory and shows positive development. Continue to build on what you have learned and challenge yourself to improve further.',
                'Hi {name}, your {task} outcome is satisfactory and reflects your growing capability. As you progress, focus on consolidating your strengths and expanding your knowledge base.',
                'Hi {name}, your {task} is satisfactory and shows you are on a positive learning trajectory. Keep developing your skills and seeking opportunities to enhance your performance.',
                'Hi {name}, your {task} submission is satisfactory and indicates ongoing development. You are building competence and are encouraged to continue stretching your abilities.',
                'Hi {name}, your {task} work is satisfactory and reflects solid progress. Keep focusing on growth and take every opportunity to strengthen your workplace capabilities.',
                'Hi {name}, your {task} is satisfactory and shows you are developing well. As you move forward, aim to deepen your engagement and refine your skills.',
                'Hi {name}, your {task} outcome is satisfactory and demonstrates your commitment to learning. Continue to grow and build on the foundation you have established.'
            ],
            'professional': [
                'Hi {name}, your performance in {task} is assessed as satisfactory and meets the competency requirements for this unit. You have demonstrated appropriate application of skills and knowledge in accordance with workplace standards.',
                'Hi {name}, your {task} submission has been assessed as satisfactory, indicating that you have achieved the required level of competence. Your work aligns with industry expectations and relevant assessment criteria.',
                'Hi {name}, your {task} work is assessed as satisfactory and demonstrates that you have met the learning outcomes for this assessment. Your performance is consistent with unit requirements.',
                'Hi {name}, your {task} has been assessed as satisfactory and confirms your competence in the required skill areas. You have fulfilled the assessment criteria appropriately.',
                'Hi {name}, your {task} submission is assessed as satisfactory and meets the standards set out in the unit descriptor. You have demonstrated sufficient competence.',
                'Hi {name}, your {task} performance is assessed as satisfactory and indicates that you have achieved the necessary competencies. Your work reflects appropriate understanding and application.',
                'Hi {name}, your {task} has been assessed as satisfactory and aligns with the expected benchmarks for this unit. You have met the required performance standards.',
                'Hi {name}, your {task} work is assessed as satisfactory and demonstrates that you have fulfilled the competency requirements. Your submission meets the assessment specifications.',
                'Hi {name}, your {task} submission is assessed as satisfactory and shows that you have achieved competence in the relevant skill areas. You have met the unit expectations.',
                'Hi {name}, your {task} performance is assessed as satisfactory and confirms your ability to meet the required standards. You have demonstrated appropriate workplace competence.'
            ],
            'warm': [
                'Hi {name}, it is great to see your work on {task}—you have done a satisfactory job and I can see the effort you are putting in! You are really starting to find your feet.',
                'Hi {name}, wonderful effort on {task}—this is satisfactory work and you should be pleased! You are growing in confidence and skill, and it is lovely to watch your progress.',
                'Hi {name}, I am so pleased with your {task} work—it is satisfactory and shows real dedication! You are developing nicely and I am excited to see where you go next.',
                'Hi {name}, your {task} is satisfactory and I can see how much you are learning! Keep up the great work—you are doing really well.',
                'Hi {name}, well done on {task}! Your satisfactory work reflects genuine care and effort, and I am delighted to see you progressing so positively.',
                'Hi {name}, it is wonderful to see your {task} work—satisfactory and full of promise! You are growing every day and it is a pleasure to support your journey.',
                'Hi {name}, your {task} is satisfactory and I am genuinely impressed by your commitment! You are building skills beautifully and should feel proud of your progress.',
                'Hi {name}, lovely work on {task}—your satisfactory performance shows you are really engaging with the learning! I am excited to see your continued development.',
                'Hi {name}, your {task} is satisfactory and truly reflects your positive attitude and effort! You are doing wonderfully and I look forward to your future achievements.',
                'Hi {name}, I am thrilled to see your {task} work—it is satisfactory and shows how much you are growing! Keep up the fantastic effort and enthusiasm.'
            ],
            'balanced': [
                'Hi {name}, your work on {task} is satisfactory and demonstrates solid understanding of the core concepts. Moving forward, consider deepening your engagement with more complex scenarios to further strengthen your skills.',
                'Hi {name}, your {task} submission is satisfactory and meets the current expectations. To continue improving, aim to refine your attention to detail and explore additional resources that support your learning.',
                'Hi {name}, your {task} is satisfactory and shows good foundational knowledge. As you progress, focus on expanding your practical application and integrating feedback to enhance your performance.',
                'Hi {name}, your {task} work is satisfactory and reflects appropriate understanding. For ongoing development, consider reviewing areas of complexity and practicing skills in varied contexts.',
                'Hi {name}, your {task} outcome is satisfactory and indicates competent completion. To build further, aim to strengthen critical thinking and seek opportunities to apply concepts more creatively.',
                'Hi {name}, your {task} submission is satisfactory and meets the required benchmarks. Moving ahead, focus on consolidating your strengths and addressing any areas where additional practice would benefit you.',
                'Hi {name}, your {task} is satisfactory and shows that you have grasped the key ideas. To advance, consider seeking additional feedback and challenging yourself with more advanced tasks.',
                'Hi {name}, your {task} work is satisfactory and demonstrates steady progress. As you continue, aim to deepen your understanding and apply skills with greater independence and confidence.',
                'Hi {name}, your {task} is satisfactory and reflects solid effort. For further growth, focus on refining your techniques and exploring how concepts apply in broader workplace situations.',
                'Hi {name}, your {task} submission is satisfactory and shows competent performance. To continue developing, consider identifying specific areas for improvement and setting goals for future assessments.'
            ],
            'random': []
        };

        commentsByTone.random = Object.keys(commentsByTone).filter(key => key !== 'random').flatMap(key => commentsByTone[key]);

        const toneColors = {
            random: { bg: '#F0EFFF', border: '#6C63FF' },
            short: { bg: '#E8F8F0', border: '#2ECC71' },
            encouraging: { bg: '#FEF5E7', border: '#F39C12' },
            detailed: { bg: '#EBF5FB', border: '#3498DB' },
            growth: { bg: '#EAFAF1', border: '#27AE60' },
            professional: { bg: '#ECF0F1', border: '#34495E' },
            warm: { bg: '#FADBD8', border: '#E74C3C' },
            balanced: { bg: '#F4ECF7', border: '#9B59B6' }
        };

        const unusedComments = {};

        function initUnused() {
            for (let tone in commentsByTone) {
                unusedComments[tone] = [...commentsByTone[tone]];
            }
        }
        initUnused();

        function generateComment(name, task, tone = 'random') {
            if (!name || !task) return 'Please enter both name and task.';
            if (unusedComments[tone].length === 0) {
                unusedComments[tone] = [...commentsByTone[tone]];
            }
            const pool = unusedComments[tone];
            const randomIndex = Math.floor(Math.random() * pool.length);
            const template = pool[randomIndex];
            pool.splice(randomIndex, 1);
            return template.replaceAll('{name}', name).replaceAll('{task}', task);
        }

        function countWords(text) {
            return text.trim().split(/\s+/).filter(word => word.length > 0).length;
        }

        function applyToneColors(tone) {
            const output = document.getElementById('output');
            const colors = toneColors[tone] || toneColors.random;
            output.style.setProperty('background-color', colors.bg, 'important');
            output.style.setProperty('border-color', colors.border, 'important');
            output.style.setProperty('border-width', '3px', 'important');
            output.style.setProperty('border-style', 'solid', 'important');
        }

        function resetUsedComments() {
            initUnused();
            const successMsg = document.getElementById('successMsg');
            successMsg.textContent = '✓ Comment history reset! All 80 comments available again.';
            successMsg.style.display = 'block';
            setTimeout(() => { successMsg.style.display = 'none'; }, 3000);
        }

        document.getElementById('generateBtn').addEventListener('click', () => {
            const name = document.getElementById('nameInput').value.trim();
            const task = document.getElementById('taskSelect').value;
            const tone = document.getElementById('toneSelect').value;
            const output = document.getElementById('output');
            
            const comment = generateComment(name, task, tone);
            output.value = comment;
            
            const wordCount = countWords(comment);
            document.getElementById('wordCount').textContent = `${wordCount} words`;
            
            applyToneColors(tone);
        });

        document.getElementById('copyBtn').addEventListener('click', () => {
            const output = document.getElementById('output');
            if (output.value) {
                output.select();
                document.execCommand('copy');
                const successMsg = document.getElementById('successMsg');
                successMsg.textContent = '✓ Copied to clipboard!';
                successMsg.style.display = 'block';
                setTimeout(() => { successMsg.style.display = 'none'; }, 2000);
            }
        });

        document.getElementById('resetBtn').addEventListener('click', resetUsedComments);

        document.getElementById('toneSelect').addEventListener('change', (e) => {
            const output = document.getElementById('output');
            if (output.value) {
                applyToneColors(e.target.value);
            }
        });
    </script>
</body>
</html>
