<div class="en post-container">
    <style>
        .tab-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 15px;
            background: #f5f5f5;
            border-radius: 8px;
        }

        .tab {
            padding: 12px 18px;
            font-weight: bold;
            border-radius: 8px;
            background: #e0e0e0;
            cursor: pointer;
            transition: background 0.3s ease-in-out, transform 0.2s;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
        }

        .tab:hover, .tab.active {
            background: #0073e6;
            color: white;
            transform: scale(1.05);
        }

        .content {
            display: none;
            padding: 25px;
            border: 1px solid #ddd;
            background: white;
            border-radius: 8px;
            margin-top: 15px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
            opacity: 0;
            transform: translateY(10px);
            transition: opacity 0.3s ease-in-out, transform 0.3s;
        }

        .content.active {
            display: block;
            opacity: 1;
            transform: translateY(0);
        }

        h1, h2, h3 {
            color: #333;
        }

        ul {
            padding-left: 20px;
        }

        ul li {
            margin-bottom: 8px;
        }

    </style>

    <div class="tab-container">
        <div class="tab active" onclick="showTab('senthil')">Senthil Kumar</div>
        <div class="tab" onclick="showTab('himanshu')">Himanshu Verma</div>
        <div class="tab" onclick="showTab('basapuram')">Basapuram Kumar</div>
    </div>

    <section id="senthil" class="content active">
        <h1>About Senthil Kumar</h1>
        <p><strong>Senior Staff Software Engineer</strong> with expertise in <strong>Hadoop, Spark, Kafka, and Big Data</strong>. Senthil has significantly contributed to open-source Apache projects.</p>
        
        <h2>Experience</h2>
        <ul>
            <li><strong>Acceldata (2024–Present)</strong>: Working on Open-Source Data Platform (ODP), enhancing Spark query performance.</li>
            <li><strong>Visa (2022–2024)</strong>: Developed a Developer Sandbox for remote debugging in GenAI applications.</li>
            <li><strong>Cloudera (2016–2021)</strong>: Backline engineer for Apache Spark, resolving complex issues.</li>
        </ul>
        
        <h2>Open Source Contributions</h2>
        <ul>
            <li>Apache Spark: SPARK-38213, SPARK-36604</li>
            <li>Apache Solr: SOLR-16817</li>
            <li>Apache Knox: KNOX-3043</li>
        </ul>
        
        <h2>Technical Skills</h2>
        <p>C++, Java, Python, Spark, Kafka, Hadoop, Solr, Docker</p>
    </section>

    <section id="himanshu" class="content">
        <h1>About Himanshu Verma</h1>
        <p><strong>Software Engineer at Acceldata</strong> specializing in Big Data, Hadoop, and cloud-based solutions.</p>
        
        <h2>Current Role</h2>
        <ul>
            <li>Developing Ambari Mpack to integrate Airflow, JupyterHub, and MLflow.</li>
            <li>Enhancing ODP’s Hadoop distribution with new features.</li>
            <li>Automating migrations from Zeppelin to JupyterHub & Oozie to Airflow.</li>
        </ul>
        
        <h2>Previous Experience</h2>
        <ul>
            <li><strong>Wipro (2020–2022)</strong>: Worked as an Application Support Analyst for British Petroleum.</li>
        </ul>
        
        <h2>Open Source Contributions</h2>
        <ul>
            <li>Resolved HBase shell logging issue in Apache Ambari (PR #3835).</li>
        </ul>
        
        <h2>Technical Skills</h2>
        <p>Hadoop, Spark, Airflow, Hive, Python, SQL, Shell Scripting</p>
    </section>

    <section id="basapuram" class="content">
        <h1>About Basapuram Kumar</h1>
        <p><strong>Senior Staff Engineer at Acceldata</strong> with 10+ years of experience in Big Data technologies.</p>
        
        <h2>Current Role</h2>
        <ul>
            <li>Developing Acceldata’s Hadoop distribution (ODP).</li>
            <li>Managing Apache components like Hive, Kafka, Ranger, and Bigtop.</li>
            <li>Providing technical solutions for cluster upgrades and data migrations.</li>
        </ul>
        
        <h2>Previous Experience</h2>
        <ul>
            <li><strong>Dremio (2021–2022)</strong>: Provided technical support for query optimizations.</li>
            <li><strong>Hortonworks (2018–2021)</strong>: Developed MySQL support for HDP Dataplane Platform.</li>
            <li><strong>MapR (2016–2018)</strong>: Worked on SQL optimizations for Hadoop clusters.</li>
        </ul>
        
        <h2>Certifications</h2>
        <ul>
            <li>Oracle Certified Java SE 6 Programmer (OCJP)</li>
            <li>MapR Certified Hadoop Developer</li>
            <li>Hortonworks Certified Hadoop Developer</li>
        </ul>
        
        <h2>Technical Skills</h2>
        <p>Java, Python, Hadoop, Impala, AWS, GCP, SQL, Kubernetes</p>
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
