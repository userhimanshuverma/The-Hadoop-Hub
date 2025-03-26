<div class="en post-container">
    <style>
        .tab-container {
            display: flex;
            justify-content: space-around;
            cursor: pointer;
            background: #f5f5f5;
            padding: 10px;
        }
        .tab {
            padding: 10px 20px;
            font-weight: bold;
            border-radius: 5px;
        }
        .tab:hover, .tab.active {
            background: #0073e6;
            color: white;
        }
        .content {
            display: none;
            padding: 20px;
            border: 1px solid #ddd;
        }
        .content.active {
            display: block;
        }
    </style>

    <div class="tab-container">
        <div class="tab active" onclick="showTab('senthil')">Senthil Kumar</div>
        <div class="tab" onclick="showTab('himanshu')">Himanshu Verma</div>
        <div class="tab" onclick="showTab('basapuram')">Basapuram Kumar</div>
    </div>
    
    <section id="senthil" class="content active">
        <h1>About Senthil Kumar</h1>
        <p><strong>Senior Staff Software Engineer</strong> with expertise in <strong>Hadoop, Spark, Kafka, and Big Data</strong>. With extensive experience in distributed computing and performance optimization, Senthil has contributed significantly to various open-source Apache projects.</p>
        
        <h2>Experience</h2>
        <p><strong>Acceldata Pvt Ltd (May 2024 – Present)</strong></p>
        <ul>
            <li>Contributing to Spark, Hadoop, Knox, and Kafka as part of Acceldata’s <strong>Open-Source Data Platform (ODP)</strong>.</li>
            <li>Enhancing Spark query performance through <strong>Gluten Velox</strong> integration.</li>
        </ul>
        
        <p><strong>Visa Data Platform Pvt Ltd (Aug 2022 – May 2024)</strong></p>
        <ul>
            <li>Developed a <strong>Developer Sandbox</strong> for remote debugging within GenAI applications.</li>
            <li>Built an SQL CoPilot tool to <strong>automate metadata collection</strong> across internal data clusters.</li>
            <li>Led a team of 4, resolving issues in <strong>Apache Solr and Spark</strong>.</li>
        </ul>
        
        <p><strong>Cloudera India Pvt Ltd (Oct 2016 – Sep 2021)</strong></p>
        <ul>
            <li>Backline engineer for <strong>Apache Spark</strong>, troubleshooting complex issues.</li>
            <li>Developed internal tools to <strong>automate Hadoop ecosystem issue detection</strong>.</li>
            <li>Resolved critical issues in Hadoop, Spark, Kafka, Hive, and Solr.</li>
        </ul>
        
        <h2>Open Source Contributions</h2>
        <p>Senthil has actively contributed to multiple Apache projects:</p>
        <ul>
            <li><strong>Apache Spark:</strong> SPARK-38213, SPARK-36604, SPARK-36996</li>
            <li><strong>Apache Solr:</strong> SOLR-16817, SOLR-16826</li>
            <li><strong>Apache Knox:</strong> KNOX-3043, KNOX-3044</li>
        </ul>
        
        <h2>Education</h2>
        <p><strong>M.E. in Computer Science</strong> – Thiagaraja College of Engineering (2007 – 2009)</p>
        <p><strong>B.Tech. in Information Technology</strong> – Dhanalakshmi College of Engineering (2002 – 2006)</p>
        
        <h2>Strengths</h2>
        <p><strong>Hard-working, Eye for detail, Motivator & Leader</strong></p>
        <p><strong>Technical Skills:</strong> C++, Java, Python, Shell Scripting, Spark, Kafka, Hadoop, Solr, Docker</p>
        </section>
        
    <section id="himanshu" class="content">
            <h2>About Himanshu Verma</h2>
    
        <h3>Professional Summary</h3>
        <p>Himanshu Verma is a <strong>Software Engineer at Acceldata</strong> with expertise in 
           <strong>Big Data technologies, the Hadoop ecosystem, and cloud-based solutions</strong>. 
           He has a strong background in <strong>Apache Airflow, JupyterHub, MLflow, Apache Spark, and Apache Hive</strong>, 
           actively contributing to Acceldata’s <strong>Open Source Data Platform (ODP)</strong>.
        </p>
    
        <h3>Current Role</h3>
        <p>At <strong>Acceldata</strong>, Himanshu has been instrumental in:</p>
        <ul>
            <li>Developing <strong>Ambari Mpack</strong> to integrate <strong>Apache Airflow, JupyterHub, and MLflow</strong> into the Hadoop ecosystem.</li>
            <li>Engineering <strong>RPMs and DEBs</strong> for seamless software packaging and deployment.</li>
            <li>Enhancing <strong>ODP’s Hadoop distribution</strong> by implementing new features, optimizing performance, and resolving issues.</li>
            <li>Automating workflow migrations from <strong>Zeppelin to JupyterHub</strong> and <strong>Oozie to Apache Airflow</strong>, improving efficiency.</li>
            <li>Deploying and configuring <strong>Hadoop ecosystem</strong> components on virtual machines, integrating <strong>Apache Iceberg with Hive</strong> for better data management.</li>
        </ul>
    
        <h3>Previous Experience</h3>
        <p>Before joining Acceldata, Himanshu worked at <strong>Wipro</strong> as a <strong>Junior Developer and Application Support Analyst</strong> for <strong>British Petroleum</strong>, where he:</p>
        <ul>
            <li>Managed <strong>critical IT infrastructure</strong>, including virtual machines and enterprise applications.</li>
            <li>Configured <strong>Azure-based applications</strong>, handled <strong>SSL certificates</strong>, and managed <strong>firewall connectivity</strong>.</li>
            <li>Provided technical support, <strong>resolved incidents via ServiceNow</strong>, and contributed to software deployment.</li>
        </ul>
        <p>Additionally, he interned as a <strong>Site Reliability Engineer</strong>, working on <strong>Hadoop cluster deployments</strong>, 
           system optimizations, and interactive UI development.</p>
    
        <h3>Education</h3>
        <ul>
            <li><strong>M.Tech in Computer Science (Data Science)</strong> – Indian Institute of Information Technology, Lucknow</li>
            <li><strong>B.Tech in Computer Science and Engineering</strong> – SRM Institute of Science and Technology</li>
        </ul>
    
        <h3>Publications</h3>
        <ul>
            <li><strong>Automated Summarization and Question Generation for Efficient Information Extraction</strong> – 
                <a href="#">Read here</a>
            </li>
        </ul>
    
        <h3>Open Source Contributions</h3>
        <ul>
            <li>Resolved <strong>HBase shell logging issue</strong> in <strong>Apache Ambari (PR #3835)</strong></li>
        </ul>
    
        <h3>Interests & Expertise</h3>
        <p>Himanshu is passionate about <strong>Big Data solutions, cloud infrastructure, and workflow automation</strong>. 
           He continues to explore and develop cutting-edge technologies to enhance <strong>data engineering and analytics workflows</strong>.
        </p>
    </section>
    
    <section id="basapuram" class="content">
        <h2>About Basapuram Kumar</h2>

        <h3>Professional Summary</h3>
        <p>Basapuram Kumar is a <strong>Senior Staff Engineer at Acceldata</strong> with over <strong>10 years of experience</strong> 
           in implementing and supporting <strong>Big Data technologies</strong>. He has extensive expertise in integrating 
           Apache projects into native platforms like <strong>Hortonworks (HDP) and Acceldata’s Open Data Platform (ODP)</strong>, 
           troubleshooting, and root cause analysis (RCA).
        </p>
    
        <h3>Current Role</h3>
        <p>At <strong>Acceldata</strong>, Basapuram has been working on:</p>
        <ul>
            <li>Developing and managing the <strong>ODP platform</strong>, Acceldata’s Apache Hadoop distribution.</li>
            <li>Handling major <strong>Hadoop stack components</strong> such as Hive, Impala, Druid, Hue, Kafka, Ranger, Ambari, and Bigtop.</li>
            <li>Managing <strong>product releases, PR reviews</strong>, and team coordination.</li>
            <li>Providing technical solutions for <strong>customer escalations, cluster upgrades, and data migrations</strong>.</li>
            <li>Performing extensive sustenance activities and <strong>troubleshooting</strong> for Apache ecosystem components.</li>
        </ul>
    
        <h3>Previous Experience</h3>
        <p>Before joining Acceldata, Basapuram worked in various roles across leading organizations:</p>
        
        <h4>Dremio Corporation (Dec 2021 – Dec 2022)</h4>
        <ul>
            <li>Provided technical support for <strong>Dremio</strong>, resolving issues related to <strong>installation, configuration, and integration</strong>.</li>
            <li>Optimized <strong>Dremio SQL queries</strong> and provided best practice recommendations.</li>
            <li>Assisted engineering teams with <strong>bug analysis, workarounds, and source code fixes</strong>.</li>
        </ul>
    
        <h4>Hortonworks / Cloudera Data Platform (Mar 2018 – Dec 2021)</h4>
        <ul>
            <li>Developed additional <strong>MySQL database support</strong> for the HDP Dataplane Platform.</li>
            <li>Enhanced <strong>Docker-based containerized services</strong> for HDP.</li>
            <li>Automated <strong>HDP cluster registration</strong> for QE test automation.</li>
            <li>Led the development of one-click automation scripts for <strong>CDP and DataLakes creation on AWS</strong>.</li>
            <li>Served as <strong>Technical Account Manager (TAM)</strong> for key enterprise clients.</li>
        </ul>
    
        <h4>MapR Data Technologies (Mar 2016 – Mar 2018)</h4>
        <ul>
            <li>Provided support for <strong>MapR SQL</strong> and managed large-scale Hadoop cluster installations.</li>
            <li>Automated <strong>cluster creation</strong> using Ansible scripts.</li>
            <li>Worked on customer-specific <strong>PoCs and use case implementations</strong>.</li>
        </ul>
    
        <h4>Tata Consultancy Services (Nov 2013 – Mar 2016)</h4>
        <ul>
            <li>Developed and executed multiple <strong>Hadoop PoCs</strong> for enterprise customers.</li>
            <li>Performed large-scale <strong>data migrations</strong> from RDBMS to Hadoop clusters.</li>
            <li>Conducted <strong>internal Hadoop training sessions</strong> for TCS employees.</li>
        </ul>
    
        <h3>Education</h3>
        <ul>
            <li><strong>MCA in Computer Science & Engineering</strong> – JNTU College of Engineering, Anantapur, India (2013)</li>
        </ul>
    
        <h3>Key Competencies & Skills</h3>
        <ul>
            <li><strong>Big Data Platforms:</strong> Hortonworks, MapR, Cloudera, Apache Hadoop</li>
            <li><strong>Operating Systems:</strong> Linux, Mac</li>
            <li><strong>Programming Languages:</strong> Java, Python</li>
            <li><strong>Databases:</strong> MySQL, PostgreSQL, Oracle</li>
            <li><strong>Others:</strong> AWS, GCP, SQL, Shell Scripting, Ansible, Angular, TypeScript, Docker, Kubernetes</li>
        </ul>
    
        <h3>Certifications</h3>
        <ul>
            <li><strong>Oracle Certified Professional, Java SE 6 Programmer (OCJP)</strong> – Dec 2014</li>
            <li><strong>MapR Certified Hadoop Developer</strong> – June 2015</li>
            <li><strong>Hortonworks Certified Hadoop Developer</strong> – Dec 2015</li>
        </ul>
    
        <h3>Publications</h3>
        <ul>
            <li><strong>Enhancing Performance of Hadoop-Based Data Lakes using Apache Iceberg</strong> – 
                <a href="#">Read here</a>
            </li>
        </ul>
    
        <h3>Core Strengths</h3>
        <ul>
            <li>Technical Troubleshooting & Problem-Solving</li>
            <li>Quick Learner & Hardworking</li>
            <li>Commitment to Quality & Self-Motivation</li>
        </ul>
    
    </section>
    
    <script>
        function showTab(id) {
            document.querySelectorAll('.content').forEach(el => el.classList.remove('active'));
            document.querySelectorAll('.tab').forEach(el => el.classList.remove('active'));
            
            document.getElementById(id).classList.add('active');
            event.target.classList.add('active');
        }
    </script>
</div>
