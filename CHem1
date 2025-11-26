<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>大学科学复习 - ChemReview Pro</title>
    <!-- 引入 Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- 配置 Tailwind 以使用 Inter 字体和自定义主题 -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        :root {
            --color-primary: #166534; /* Deep Forest Green - 森林绿 */
            --color-secondary: #ca8a04; /* Warm Amber/Gold - 暖琥珀 */
            --color-background: #f7fee7; /* Pale Mint/Green - 极浅薄荷绿 */
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--color-background);
        }
        .card {
            transition: all 0.3s ease;
            cursor: pointer;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px -5px rgba(22, 101, 52, 0.2); /* 森林绿阴影 */
        }
        /* 详细内容区域的标题颜色 */
        #detail-title {
            color: var(--color-primary);
        }
        /* 自定义英雄区渐变背景 */
        .hero-gradient {
            background-image: linear-gradient(to top, #f0fdf4, #f7fee7); /* 柔和的浅绿渐变 */
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- 顶部导航栏/标题 - 深森林绿背景 -->
    <header class="bg-green-900 shadow-xl sticky top-0 z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <h1 class="text-3xl font-extrabold text-white">
                <span class="text-amber-500">Nature</span><span class="text-green-300">Review</span>
            </h1>
            <nav class="hidden md:block">
                <a href="#topics" class="text-green-200 hover:text-amber-300 mx-3 font-medium transition">复习主题 / Topics</a>
                <a href="#about" class="text-green-200 hover:text-amber-300 mx-3 font-medium transition">关于 / About</a>
            </nav>
        </div>
    </header>

    <!-- 主体内容 -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10">

        <!-- 英雄区/介绍 - 渐变背景，圆角 -->
        <section class="text-center py-20 hero-gradient rounded-3xl shadow-2xl mb-12">
            <h2 class="text-4xl sm:text-5xl font-extrabold text-gray-900 mb-4">
                探索科学之美 / Explore the Beauty of Science
            </h2>
            <p class="text-xl text-gray-700 max-w-3xl mx-auto mb-8">
                精选大学核心科学要点，以地球之名，助您高效准备与深度学习。/ Key concepts for high-efficiency study.
            </p>
            <button onclick="document.getElementById('topics').scrollIntoView({ behavior: 'smooth' });"
                class="bg-amber-600 hover:bg-amber-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transform transition duration-300 hover:scale-105">
                开始复习 / Start Review
            </button>
        </section>

        <!-- 主题卡片网格 -->
        <section id="topics" class="mb-12">
            <h3 class="text-3xl font-bold text-gray-800 mb-8 border-b-2 border-green-600 pb-3">核心复习主题 / Core Review Topics</h3>
            <div id="topic-grid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 xl:grid-cols-5 gap-6">

                <!-- 1. 通用化学 - 森林绿 -->
                <div class="card bg-white p-6 rounded-xl shadow-md border-t-8 border-green-600 hover:border-green-700" data-topic="gen-chem">
                    <h4 class="text-xl font-semibold text-gray-900 mb-2 flex items-center">
                        <svg class="w-6 h-6 text-green-600 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-2h2v2zm0-4h-2V7h2v6z"></path></svg>
                        通用化学 / General Chemistry
                    </h4>
                    <p class="text-gray-500 text-sm">原子结构、化学键、化学计量学 / Atomic structure, Bonding, Stoichiometry</p>
                </div>

                <!-- 2. 有机化学 - 琥珀色/泥土色 -->
                <div class="card bg-white p-6 rounded-xl shadow-md border-t-8 border-amber-600 hover:border-amber-700" data-topic="org-chem">
                    <h4 class="text-xl font-semibold text-gray-900 mb-2 flex items-center">
                        <svg class="w-6 h-6 text-amber-600 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M18.99 5h-14c-1.1 0-1.99.9-1.99 2v10c0 1.1.89 2 1.99 2h14c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm-10 11H7V8h1.99v8zm2.5-4h-2.5v-2h2.5v2zm4 4h-2.5v-2h2.5v2zm2.5-4h-2.5v-2h2.5v2z"></path></svg>
                        有机化学 / Organic Chemistry
                    </h4>
                    <p class="text-gray-500 text-sm">官能团、命名法、反应机理 / Functional groups, Nomenclature, Mechanisms</p>
                </div>

                <!-- 3. 物理化学 - 板岩灰/岩石色 -->
                <div class="card bg-white p-6 rounded-xl shadow-md border-t-8 border-slate-500 hover:border-slate-700" data-topic="phy-chem">
                    <h4 class="text-xl font-semibold text-gray-900 mb-2 flex items-center">
                        <svg class="w-6 h-6 text-slate-500 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm0 18.2c-3.14-1.47-5.54-4.23-6.8-7.72C5.92 9.54 7.57 6.47 12 4.47c4.43 2 6.08 5.07 5.8 7.01-1.26 3.49-3.66 6.25-6.8 7.72z"></path></svg>
                        物理化学 / Physical Chemistry
                    </h4>
                    <p class="text-gray-500 text-sm">热力学、化学动力学、量子化学 / Thermodynamics, Kinetics, Quantum chemistry</p>
                </div>

                <!-- 4. 分析化学 - 苔藓绿/青色 -->
                <div class="card bg-white p-6 rounded-xl shadow-md border-t-8 border-teal-600 hover:border-teal-700" data-topic="ana-chem">
                    <h4 class="text-xl font-semibold text-gray-900 mb-2 flex items-center">
                        <svg class="w-6 h-6 text-teal-600 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm2 16H8v-2h8v2zm0-4H8v-2h8v2zm-3-5V3.5L18.5 9H13z"></path></svg>
                        分析化学 / Analytical Chemistry
                    </h4>
                    <p class="text-gray-500 text-sm">光谱学、电化学、分离技术 / Spectroscopy, Electrochemistry, Separation techniques</p>
                </div>
                
                <!-- 5. 大学生物 - 鲜嫩的叶绿色 -->
                <div class="card bg-white p-6 rounded-xl shadow-md border-t-8 border-lime-600 hover:border-lime-700" data-topic="bio-chem">
                    <h4 class="text-xl font-semibold text-gray-900 mb-2 flex items-center">
                        <svg class="w-6 h-6 text-lime-600 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15h2v-2h-2v2zm0-4h2V7h-2v6z"></path></svg>
                        大学生物 / College Biology
                    </h4>
                    <p class="text-gray-500 text-sm">细胞、分子生物学、遗传与进化 / Cells, Genetics, Evolution</p>
                </div>

            </div>
        </section>

        <!-- 详情展示区 -->
        <section id="review-detail" class="bg-white p-8 rounded-xl shadow-2xl hidden">
            <h3 id="detail-title" class="text-3xl font-bold mb-4"></h3>
            <div id="detail-content" class="prose max-w-none">
                <!-- 详细复习内容和链接将通过 JavaScript 注入 -->
            </div>
            <button onclick="hideDetail()" class="mt-6 bg-gray-200 hover:bg-gray-300 text-gray-800 font-medium py-2 px-4 rounded-lg transition duration-150">
                返回主题列表 / Back to Topics
            </button>
        </section>

    </main>

    <!-- 底部 - 深森林绿背景 -->
    <footer class="bg-green-900 text-white mt-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8 text-center">
            <p id="about" class="text-sm">© 2024 NatureReview | 探索自然科学之美 / Explore the Beauty of Natural Sciences</p>
            <p class="text-xs mt-2 text-green-300">所有内容仅供学习参考，请以您的教材和课堂笔记为准。 / Content for reference only. Please rely on your textbooks and lecture notes.</p>
        </div>
    </footer>

    <script>
        // 定义复习内容数据
        const reviewTopics = {
            "gen-chem": {
                title: "通用化学：基础概念回顾 / General Chemistry: Core Concepts",
                content: `
                    <h4>原子结构与周期性 / Atomic Structure and Periodicity</h4>
                    <ul>
                        <li><span class="font-bold">量子数 (Quantum Numbers):</span> 主量子数(n)、角量子数(l)、磁量子数(m_l)、自旋量子数(m_s)及其意义 (n, l, m_l, m_s and their significance).</li>
                        <li><span class="font-bold">电子排布 (Electron Configuration):</span> Aufbau原理 (Aufbau Principle)、Hund规则 (Hund's Rule) 和 Pauli不相容原理 (Pauli Exclusion Principle).</li>
                        <li><span class="font-bold">周期性 (Periodicity):</span> 原子半径 (Atomic Radius)、电离能 (Ionization Energy)、电子亲和性 (Electron Affinity) 和 电负性 (Electronegativity) 在周期表中的趋势 (trends in the periodic table).</li>
                    </ul>
                    <h4>化学键与分子结构 / Chemical Bonding and Molecular Structure</h4>
                    <ul>
                        <li><span class="font-bold">VSEPR理论 (VSEPR Theory):</span> 预测分子几何形状 (Predicting molecular geometry, e.g., tetrahedral, trigonal bipyramidal).</li>
                        <li><span class="font-bold">杂化轨道 (Hybrid Orbitals):</span> sp, sp2, sp3 等杂化类型的形成与应用 (Formation and application of sp, sp2, sp3 hybridization).</li>
                        <li><span class="font-bold">分子间作用力 (Intermolecular Forces):</span> 范德华力 (van der Waals forces)、氢键 (Hydrogen Bonding) 及其对物质性质的影响 (their effects on substance properties).</li>
                    </ul>
                    <h4>化学计量学与溶液 / Stoichiometry and Solutions</h4>
                    <ul>
                        <li><span class="font-bold">摩尔概念 (Mole Concept):</span> 质量 (mass)、摩尔数 (moles) 和 粒子数 (number of particles) 之间的转换 (conversion).</li>
                        <li><span class="font-bold">溶液浓度 (Solution Concentration):</span> 摩尔浓度 (Molarity - M)、质量百分比 (Mass Percent) 和 摩尔分数 (Mole Fraction).</li>
                        <li><span class="font-bold">酸碱平衡 (Acid-Base Equilibria):</span> Ka, Kb, pH, pOH 的计算，以及缓冲溶液原理 (Calculations of Ka, Kb, pH, pOH, and the principle of buffer solutions).</li>
                    </ul>
                `,
                links: [
                    { name: "Khan Academy 通用化学课程 (英文)", url: "https://www.khanacademy.org/science/chemistry" },
                    { name: "NIST 化学 WebBook (参考数据)", url: "https://webbook.nist.gov/chemistry/" },
                    { name: "MIT OpenCourseWare - 普适化学讲座 (英文)", url: "https://ocw.mit.edu/courses/5-111sc-principles-of-chemical-science-fall-2014/" },
                    { name: "LibreTexts - 通用化学教材 (英文)", url: "https://chem.libretexts.org/Bookshelves/General_Chemistry" }
                ]
            },
            "org-chem": {
                title: "有机化学：结构与反应核心 / Organic Chemistry: Structure and Reactions",
                content: `
                    <h4>基础结构与官能团 / Basic Structures and Functional Groups</h4>
                    <ul>
                        <li><span class="font-bold">命名法 (Nomenclature):</span> IUPAC 系统命名法 (IUPAC nomenclature for alkanes, alkenes, alkynes, alcohols, etc.).</li>
                        <li><span class="font-bold">立体化学 (Stereochemistry):</span> 对映异构体 (Enantiomers)、非对映异构体 (Diastereomers)、R/S 命名法 (R/S notation)、Cis/Trans 异构体 (Cis/Trans isomers).</li>
                        <li><span class="font-bold">芳香性 (Aromaticity):</span> Hückel 规则 (Hückel's Rule, 4n+2) 与芳香化合物的稳定性 (stability of aromatic compounds).</li>
                    </ul>
                    <h4>核心反应类型 / Core Reaction Types</h4>
                    <ul>
                        <li><span class="font-bold">取代反应 (Substitution):</span> 亲核取代 (Nucleophilic substitution - SN1, SN2) 及其影响因素 (influencing factors).</li>
                        <li><span class="font-bold">消除反应 (Elimination):</span> E1 和 E2 反应 (E1 and E2 reactions)，Zaitsev 规则 (Zaitsev's rule).</li>
                        <li><span class="font-bold">加成反应 (Addition):</span> 亲电加成 (Electrophilic addition, e.g., Markovnikov's rule).</li>
                        <li><span class="font-bold">羰基化学 (Carbonyl Chemistry):</span> 醛酮的亲核加成 (Nucleophilic addition to aldehydes/ketones)，酯的水解 (hydrolysis of esters)，以及 Claisen, Aldol 缩合反应 (Claisen and Aldol condensation).</li>
                    </ul>
                `,
                links: [
                    { name: "有机化学反应机理教程 (英文)", url: "https://www.organic-chemistry.org/" },
                    { name: "Master Organic Chemistry (英文博客)", url: "https://www.masterorganicchemistry.com/" },
                    { name: "ChemDraw Free Viewer (分子结构查看器)", url: "https://chemdrawdirect.perkinelmer.cloud/js/cdx_install.html" },
                    { name: "IUPAC 有机命名法指南 (英文)", url: "https://www.iupac.org/resources/nomenclature/organic/" }
                ]
            },
            "phy-chem": {
                title: "物理化学：能量与速率原理 / Physical Chemistry: Energy and Rate Principles",
                content: `
                    <h4>化学热力学 / Chemical Thermodynamics</h4>
                    <ul>
                        <li><span class="font-bold">热力学第一定律 (First Law):</span> 内能变化 (Delta U) 等于热 (q) 加上功 (w), Delta U = q + w.</li>
                        <li><span class="font-bold">热力学第二定律 (Second Law):</span> 熵 (S) 和 Gibbs 自由能 (Delta G). Gibbs 自由能的变化 Delta G = Delta H - T Delta S.</li>
                        <li><span class="font-bold">平衡常数 (Equilibrium Constant):</span> Keq 与标准 Gibbs 自由能 Delta G° 的关系: Delta G° = -RT ln Keq.</li>
                    </ul>
                    <h4>化学动力学 / Chemical Kinetics</h4>
                    <ul>
                        <li><span class="font-bold">反应级数 (Reaction Order):</span> 零级 (Zero), 一级 (First), 二级 (Second) 反应的速率方程和半衰期 (t1/2).</li>
                        <li><span class="font-bold">Arrhenius方程 (Arrhenius Equation):</span> 活化能 (Ea) 与速率常数 (k) 的关系 (k = A * exp(-Ea / RT)).</li>
                        <li><span class="font-bold">催化剂 (Catalysts):</span> 均相 (Homogeneous) 与非均相 (Heterogeneous) 催化对反应路径和活化能的影响.</li>
                    </ul>
                `,
                links: [
                    { name: "MIT OpenCourseWare 物理化学 (英文)", url: "https://ocw.mit.edu/courses/5-60-thermodynamics-kinetics-fall-2008/" },
                    { name: "基础热力学概念回顾 (英文)", url: "https://chem.libretexts.org/Bookshelves/Physical_and_Theoretical_Chemistry_Textbook_Maps/Map%3A_Physical_Chemistry_(LibreTexts)/03%3A_Thermodynamics" },
                    { name: "UC Berkeley 物理化学讲义 (英文)", url: "http://chemistry.berkeley.edu/courses/undergrad/chem-120a-b-physical-chemistry-introductory" },
                    { name: "化学动力学入门教程 (英文)", url: "https://chem.libretexts.org/Bookshelves/Physical_and_Theoretical_Chemistry_Textbook_Maps/Map%3A_Physical_Chemistry_(LibreTexts)/16%3A_Chemical_Kinetics" }
                ]
            },
            "ana-chem": {
                title: "分析化学：分离与表征技术 / Analytical Chemistry: Separation and Characterization",
                content: `
                    <h4>光谱分析法 / Spectroscopic Methods</h4>
                    <ul>
                        <li><span class="font-bold">紫外-可见光谱 (UV-Vis Spectroscopy):</span> Lambert-Beer 定律 (A = epsilon * b * c) 与定量分析 (Lambert-Beer's Law and quantitative analysis).</li>
                        <li><span class="font-bold">红外光谱 (IR Spectroscopy):</span> 官能团的特征振动频率 (Characteristic vibrational frequencies of functional groups) 与定性分析 (qualitative analysis).</li>
                        <li><span class="font-bold">核磁共振 (NMR):</span> 化学位移 (Chemical shift)、偶合常数 (Coupling constant) 和 积分面积 (Integral area) 在结构确定中的应用 (applications in structure determination).</li>
                    </ul>
                    <h4>分离技术 / Separation Techniques</h4>
                    <ul>
                        <li><span class="font-bold">色谱法基础 (Chromatography Basics):</span> 固定相 (Stationary phase)、流动相 (Mobile phase)、分配系数 (Partition coefficient)、保留时间 (Retention time).</li>
                        <li><span class="font-bold">高效液相色谱 (HPLC):</span> 反相 (Reverse phase)、正相 (Normal phase) 模式及其应用 (modes and applications).</li>
                        <li><span class="font-bold">气相色谱 (GC):</span> 适用于挥发性物质的分离 (Suitable for separating volatile substances).</li>
                    </ul>
                `,
                links: [
                    { name: "光谱技术原理概述 (英文)", url: "https://www.spectroscopynow.com/" },
                    { name: "色谱法基础教程 (英文)", url: "https://www.chromacademy.com/chromatography-training-courses.html" },
                    { name: "电化学分析基础 (英文)", url: "https://chem.libretexts.org/Bookshelves/Analytical_Chemistry/Book%3A_Analytical_Chemistry_2.1_(Harvey)/06_Electrochemical_Methods" }
                ]
            },
            "bio-chem": {
                title: "大学生物：生命科学核心 / College Biology: Core Life Sciences",
                content: `
                    <h4>细胞生物学 / Cell Biology</h4>
                    <ul>
                        <li><span class="font-bold">细胞结构与功能 (Structure and Function):</span> 原核细胞与真核细胞 (Prokaryotic vs. Eukaryotic cells)，主要细胞器 (Major organelles) 的作用。</li>
                        <li><span class="font-bold">膜运输 (Membrane Transport):</span> 被动运输 (Passive transport)、主动运输 (Active transport) 和 细胞内吞/外排 (Endo/Exocytosis)。</li>
                        <li><span class="font-bold">能量代谢 (Energy Metabolism):</span> 细胞呼吸 (Cellular respiration) 的三个阶段（糖酵解、克雷布斯循环、电子传递链）和 光合作用 (Photosynthesis) 的光反应与暗反应。</li>
                    </ul>
                    <h4>分子生物学与遗传学 / Molecular Biology & Genetics</h4>
                    <ul>
                        <li><span class="font-bold">分子结构 (Molecular Structure):</span> DNA 和 RNA 的结构 (Structure of DNA and RNA)，核酸的复制 (Replication)。</li>
                        <li><span class="font-bold">基因表达 (Gene Expression):</span> 中心法则 (Central Dogma)；转录 (Transcription)、翻译 (Translation) 的过程。</li>
                        <li><span class="font-bold">遗传学 (Genetics):</span> 孟德尔遗传定律 (Mendelian inheritance laws)，基因连锁 (Gene linkage) 和 基因突变 (Gene mutation)。</li>
                    </ul>
                    <h4>生态学与进化 / Ecology & Evolution</h4>
                    <ul>
                        <li><span class="font-bold">进化原理 (Evolution Principles):</span> 自然选择 (Natural selection)、适应 (Adaptation) 和 物种形成 (Speciation)。</li>
                        <li><span class="font-bold">生态系统 (Ecosystems):</span> 食物链/网 (Food webs/chains)、能量流 (Energy flow) 和 生物地球化学循环 (Biogeochemical cycles)。</li>
                    </ul>
                `,
                links: [
                    { name: "Khan Academy 生物学课程 (英文)", url: "https://www.khanacademy.org/science/biology" },
                    { name: "MIT OpenCourseWare - 生物学导论 (英文)", url: "https://ocw.mit.edu/courses/7-01sc-introduction-to-biology-fall-2013/" },
                    { name: "CrashCourse 生物学 YouTube 播放列表 (英文)", url: "https://www.youtube.com/playlist?list=PL3EED4C1D684FADBC" },
                    { name: "LibreTexts - 生物学教材 (英文)", url: "https://bio.libretexts.org/" }
                ]
            }
        };

        const cardElements = document.querySelectorAll('.card');
        const detailSection = document.getElementById('review-detail');
        const detailTitle = document.getElementById('detail-title');
        const detailContent = document.getElementById('detail-content');
        const topicGrid = document.getElementById('topic-grid');

        // 为每个卡片添加点击事件监听器
        cardElements.forEach(card => {
            card.addEventListener('click', () => {
                const topicKey = card.getAttribute('data-topic');
                displayDetail(topicKey);
            });
        });

        /**
         * 显示特定主题的详细复习内容
         * @param {string} key 主题的键名
         */
        function displayDetail(key) {
            const topic = reviewTopics[key];
            if (topic) {
                // 基础内容
                let htmlContent = topic.content;

                // 添加延伸学习资源链接
                if (topic.links && topic.links.length > 0) {
                    htmlContent += `
                        <h4 class="mt-8 mb-3 text-2xl font-bold text-gray-800 border-b border-green-300 pb-1">延伸学习资源 / Further Learning Resources</h4>
                        <ul class="space-y-2 list-none p-0">
                    `;
                    topic.links.forEach(link => {
                        // 确保链接是可点击的，并且在新标签页中打开
                        htmlContent += `
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-amber-600 mr-2 flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path></svg>
                                <a href="${link.url}" target="_blank" class="text-green-700 hover:text-amber-600 hover:underline font-medium break-words">${link.name}</a>
                            </li>
                        `;
                    });
                    htmlContent += `</ul>`;
                }

                // 更新内容
                detailTitle.textContent = topic.title;
                detailContent.innerHTML = htmlContent;

                // 隐藏卡片网格，显示详情区
                topicGrid.classList.add('hidden');
                detailSection.classList.remove('hidden');

                // 平滑滚动到详情区
                detailSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        /**
         * 隐藏详细内容，显示主题列表
         */
        function hideDetail() {
            detailSection.classList.add('hidden');
            topicGrid.classList.remove('hidden');

            // 平滑滚动到主题列表
            topicGrid.scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>
