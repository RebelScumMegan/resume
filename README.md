<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>John Doe</h1>
            <p>Minneapolis, MN</p>
            <p>Email: john.doe@example.com | Phone: (123) 456-7890</p>
        </header>
        <section class="experience">
            <h2>Professional Experience</h2>
            <div class="job">
                <h3>Medical Case Manager, Aliveness Project</h3>
                <p><em>April, 2021 – Present | Minneapolis, MN</em></p>
                <ul>
                    <li>Conduct comprehensive (re)assessments of case management, manage client records/files for up to 50 clients</li>
                    <li>Complete individual plans to overcome barriers to maintaining medical care</li>
                    <li>Participate in trainings/meetings/initiatives, and engage in outreach and recruitment of new clients</li>
                </ul>
            </div>
            <div class="job">
                <h3>Mental Health Worker, Headway Emotional Health</h3>
                <p><em>August, 2019 – April, 2021 | Minneapolis, MN</em></p>
                <ul>
                    <li>Lead groups of 5-10 teenagers on the topics of coping skills, relationship skills, and communication skills</li>
                    <li>Developed individualized coaching and participated in therapeutic activities with day treatment therapists</li>
                    <li>Ensured that all behavioral interventions are safe, therapeutic, documented, and accessible to all staff</li>
                    <li>Ensured that all paperwork is done in accordance with organization CTSS and Rule 29/47 guidelines</li>
                </ul>
            </div>
            <div class="job">
                <h3>Scheduling Representative, Associated Clinic of Psychology</h3>
                <p><em>April, 2019 – August, 2019 | Minneapolis, MN</em></p>
                <ul>
                    <li>Developed administrative policies and procedures to provide support for ACP medical providers</li>
                    <li>Reviewed medical provider notes, medical histories and monitored prescriptions</li>
                </ul>
            </div>
            <div class="job">
                <h3>Full-Time Infant Caretaker, Private Residence</h3>
                <p><em>April, 2018 – March, 2019 | Minneapolis, MN</em></p>
                <ul>
                    <li>Provided care and education via physical, emotional, and social activities to promote healthy infant development</li>
                </ul>
            </div>
            <div class="job">
                <h3>Program Coordinator, Hazelden Betty Ford Foundation</h3>
                <p><em>February, 2017 – February, 2018 | St Paul, MN</em></p>
                <ul>
                    <li>Managed cases for opioid programs; tracked treatment plans, drug screenings, and medication refills</li>
                    <li>Developed a patient tracking system under HIPPA compliance for medical, psychologist, and psychiatrist teams</li>
                    <li>Coordinated with multiple teams to address unique needs of patients and helped alleviate scheduling barriers</li>
                    <li>Triaged support for appropriate health services and social services referrals for individuals and families</li>
                </ul>
            </div>
            <div class="job">
                <h3>Assistant Program Manager & Crisis Prevention Trainer, Hammer Residences, Inc.</h3>
                <p><em>June, 2014 – February, 2017 | Minneapolis, MN</em></p>
                <ul>
                    <li>Upon promotion, became responsible for 6 support professionals and numerous groups of volunteers</li>
                    <li>Trained 100+ staff in crisis prevention interventions, and developed content for group and individual coaching</li>
                    <li>Partnered with training directors to create a mental health-centered approach around interactions with diverse individuals living with developmental and cognitive disabilities</li>
                    <li>Managed budgets, onsite staff, program activities and administrative reports</li>
                </ul>
            </div>
            <div class="job">
                <h3>Supervisor, Hillcrest Terrace</h3>
                <p><em>March, 2011 – May, 2014 | Minneapolis, MN</em></p>
                <ul>
                    <li>Supervised 8 direct support professionals, providing individual coaching and staff performance assessments</li>
                    <li>Managed programs and assessed needs; provided direct support for aging individuals with complex conditions</li>
                </ul>
            </div>
        </section>
        <section class="education">
            <h2>Education</h2>
            <p><strong>Bachelor of Science – Psychology</strong>, University of Phoenix; Graduated October, 2018</p>
        </section>
        <section class="volunteer">
            <h2>Volunteer Experience</h2>
            <p><strong>2015 Volunteer Fundraiser</strong> – Raised $2,000 for To Write Love on Her Arms (TWLOHA International)</p>
        </section>
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
    padding: 20px;
    background: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

header {
    text-align: center;
    margin-bottom: 20px;
}

header h1 {
    margin: 0;
    color: #333;
}

header p {
    margin: 5px 0;
}

h2 {
    color: #555;
    border-bottom: 2px solid #e8491d;
    padding-bottom: 5px;
}

h3 {
    color: #e8491d;
    margin: 0;
}

.job {
    margin-bottom: 20px;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    background: url('bullet.png') no-repeat left center;
    padding-left: 20px;
    margin: 5px 0;
}

section {
    margin-bottom: 20px;
}

@media (max-width: 768px) {
    .container {
        width: 100%;
        padding: 10px;
    }
}
