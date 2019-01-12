
<!DOCTYPE html>
<html lang="en" class="_footer-thin _header-thin-only">

<head>

<!-- begin framework head en -->

    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta charset="utf-8">
    <meta name="msapplication-config" content="/browserconfig.xml">
    <link rel="stylesheet" href="//www.wolframcdn.com/fonts/source-sans-pro/1.0/global.css">
    <link rel="stylesheet" href="/common/framework/css/framework.en.css">
    <link rel="stylesheet" href="/common/framework/css/gui.en.css">
    <script src="//www.wolframcdn.com/consent/cookie-consent.js"></script>
    <script src="/common/javascript/wal/latest/walLoad.js"></script>
    <script src="/common/framework/js/head.en.js"></script>
    <script src="/common/js/jquery/2.2.4/jquery.min.js"></script>
    <script src="/common/js/jquery/plugins/hoverintent/1.8.0/hoverintent.min.js"></script>
    <script src="/common/javascript/analytics.js"></script>

<!-- end framework head en -->



<title>RollPitchYawAngles&mdash;Wolfram Language Documentation</title>
<meta name="buildnumber" content="103">
<meta name="historydata" content="{10.2, , , }" />
<meta name="keywords" content=" bank-elevation-heading,  bank-elevation-heading angles,  Cardan angles,  extrinsic rotation angles, extrinsic rotations,  fixed axis rotation angles,  fixed axis rotations,  fixed frame rotation angles,  fixed frame rotations,  heading-elevation-bank,  heading-elevation-bank angles,  html,  orthogonal rotation,  orthogonal rotation angles,  roll-pitch-yaw,  roll-pitch-yaw angles,  yaw-pitch-roll,  yaw-pitch-roll angles" />

<meta name="description" content="RollPitchYawAngles[r] gives the roll-pitch-yaw angles {\[Alpha], \[Beta], \[Gamma]} corresponding to the rotation matrix r. RollPitchYawAngles[r, {a, b, c}] gives the roll-pitch-yaw angles {\[Alpha], \[Beta], \[Gamma]} corresponding to rotation order {a, b, c}." />
<link rel="stylesheet" href="/language-assets/css/global.css">
<link rel="stylesheet" href="/language-assets/css/iconography.css">
<link rel="stylesheet" href="/language-assets/css/in-out.css">
<link rel="stylesheet" href="/language-assets/css/header.css">
<link rel="stylesheet" href="/language-assets/css/icons.css">
<link rel="stylesheet" href="/language-assets/css/root-guide.css">
<link rel="stylesheet" href="/language-assets/css/special-styles.css">
<link rel="stylesheet" href="/language-assets/css/language-specific.css">
<link rel="stylesheet" href="/language-assets/css/man-page.css">
<link rel="stylesheet" href="/language-assets/css/clipboard.css">
<link rel="stylesheet" href="/language-assets/css/tables.css">
<link rel="stylesheet" href="/language-assets/css/footer.css">
<link rel="stylesheet" href="/language-assets/css/guide.css">
<link rel="stylesheet" href="/language-assets/css/technotes.css">
<link rel="stylesheet" href="/language-assets/css/workflows.css">
<link rel="stylesheet" href="//fonts.googleapis.com/css?family=Roboto">
<script>var baselang = 'RollPitchYawAngles.en';</script>
</head>

<body id="ref" class="function">
  
<!-- begin framework header en -->

<header id="_header">
    <div id="_header-t" class="_page-width hide__600">
        <ul class="font-size-3-4 padding-t-1-2 heirs-bar-between heirs-display-ib">
            <li><a href="http://www.wolframalpha.com/?source=nav" data-walid="GUIHeader">WolframAlpha.com</a>
            <li><a href="https://www.wolframcloud.com/?source=nav" data-walid="GUIHeader">WolframCloud.com</a>
            <li><a href="http://www.wolfram.com/resources/?source=nav" data-walid="GUIHeader">All Sites &amp; Public Resources...</a>
        </ul>
    </div>
    <div id="_header-b" class="_page-width cf">
        <h1 id="_logo">
            <a href="http://www.wolfram.com/?source=nav" data-walid="GUIHeader" class="cf display-b">
                <img src="/common/framework/img/spikey.en.png" alt="" width="48" height="50" id="_logo-spikey">
                <img src="/common/framework/img/wolfram.en.png" alt="Wolfram" width="160" height="22" id="_logo-wolfram">
                <img src="/common/framework/img/slogan.en.png" alt="Computation Meets Knowledge" width="160" height="7" id="_logo-slogan">
            </a>
        </h1>
        <nav id="_nav" class="hide heirs-float-l">

            <div id="_nav-products" class="_nav-tab">
                <a href="http://www.wolfram.com/products/?source=nav" data-walid="GUIHeader" class="_nav-l1">Products<span class="hide__1200 display-i__600"> &amp; Services</span><i class="_icon-r1-c1 hide__900"></i></a>
                <div class="_nav-tab-content">
                    <div class="_page-width padding-bt-1">
                        <div class="table width-full">
                            <div class="heirs-width-1-4 heirs-width-1-3__900">
                                <ul class="_nav-c1 _nav-hover">
                                    <li><a href="http://www.wolfram.com/wolfram-one/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r1-c12"></i></span><span>Wolfram|One</span></a>
                                    <li><a href="http://www.wolfram.com/mathematica/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r2-c1"></i></span><span>Mathematica</span></a>
                                    <li><a href="http://www.wolfram.com/development-platform/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r2-c2"></i></span><span>Development Platform</span></a>
                                    <li><a href="http://www.wolfram.com/programming-lab/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r2-c3"></i></span><span>Programming Lab</span></a>
                                    <li><a href="http://www.wolfram.com/data-science-platform/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r2-c5"></i></span><span>Data Science Platform</span></a>
                                    <li><a href="http://www.wolfram.com/finance-platform/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r2-c6"></i></span><span>Finance Platform</span></a>
                                    <li><a href="http://www.wolfram.com/system-modeler/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r2-c7"></i></span><span>SystemModeler</span></a>
                                </ul>
                                <ul class="_nav-c2">
                                    <li class="_nav-c1 _nav-hover">
                                        <ul>
                                            <li><a href="http://www.wolfram.com/enterprise-private-cloud/?source=nav" data-walid="GUIHeader" class="mini _nav-l2 _nav-has-line"><span><i class="_icon-r1-c8"></i></span><span>Enterprise Private Cloud</span></a>
                                            <li><a href="http://www.wolfram.com/mathematica-enterprise-edition/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r1-c9"></i></span><span>Enterprise Mathematica</span></a>
                                            <li><a href="http://products.wolframalpha.com/appliance/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r1-c10"></i></span><span>Wolfram|Alpha Appliance</span></a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover"><span class="mini _nav-l2"><span><i class="_icon-r1-c11"></i></span><span>Enterprise Solutions</span></span>
                                        <ul>
                                            <li><a href="http://www.wolframsolutions.com/?source=nav" data-walid="GUIHeader" class="_nav-l3">Corporate Consulting</a></li>
                                            <li><a href="http://www.wolfram.com/support/technical-services/?source=nav" data-walid="GUIHeader" class="_nav-l3">Technical Services</a></li>
                                            <li><a href="http://products.wolframalpha.com/business/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram|Alpha Business Solutions</a></li>
                                        </ul>
                                    </li>
                                    <li class="_nav-hover hide show__900"><a href="http://www.wolfram.com/education/?source=nav" data-walid="GUIHeader" class="mini _nav-l2 _exclude-from-burger"><span><i class="_icon-r2-c10"></i></span><span>Products for Education</span></a>
                                    <li class="_nav-hover hide show__900"><a href="https://datadrop.wolframcloud.com/?source=nav" data-walid="GUIHeader" class="mini _nav-l2 _exclude-from-burger"><span><i class="_icon-r2-c9"></i></span><span>Data Drop</span></a>
                                    <li class="_nav-hover hide show__900"><a href="https://datarepository.wolframcloud.com/?source=nav" data-walid="GUIHeader" class="mini _nav-l2 _exclude-from-burger"><span><i class="_icon-r3-c10"></i></span><span>Data Repository</span></a>
                                </ul>
                                <ul class="_nav-c3 border-r-n__900">
                                    <li class="_nav-hover hide__900"><a href="http://www.wolfram.com/education/?source=nav" data-walid="GUIHeader" class="mini _nav-l2 _nav-has-line"><span><i class="_icon-r2-c10"></i></span><span>Products for Education</span></a>
                                    <li class="_nav-hover"><a href="http://www.wolframalpha.com/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r2-c8"></i></span><span>Wolfram|Alpha</span></a>
                                        <ul>
                                            <li><a href="http://www.wolframalpha.com/pro/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram|Alpha Pro</a>
                                            <li><a href="http://www.wolframalpha.com/pro/problem-generator/?source=nav" data-walid="GUIHeader" class="_nav-l3">Problem Generator</a>
                                            <li><a href="http://products.wolframalpha.com/api/?source=nav" data-walid="GUIHeader" class="_nav-l3">API</a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover hide__900"><a href="https://datadrop.wolframcloud.com/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r2-c9"></i></span><span>Data Drop</span></a>
                                    <li class="_nav-hover hide__900"><a href="https://datarepository.wolframcloud.com/?source=nav" data-walid="GUIHeader" class="mini _nav-l2"><span><i class="_icon-r3-c10"></i></span><span>Data Repository</span></a>
                                    <li class="_nav-hover hide show__900"><span class="mini _nav-l2 _exclude-from-burger"><span><i class="_icon-r2-c11"></i></span><span>Mobile Apps</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/player-app/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Player</a>
                                            <li><a href="http://www.wolfram.com/cloud-app/?source=nav" target="_blank" data-walid="GUIHeader" class="_nav-l3">Wolfram Cloud App</a>
                                            <li><a href="http://products.wolframalpha.com/mobile/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram|Alpha for Mobile</a>
                                            <li><a href="http://products.wolframalpha.com/mobile/?source=nav#wapowered" data-walid="GUIHeader" class="_nav-l3">Wolfram|Alpha-Powered Apps</a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover hide show__900"><span class="mini _nav-l2 _exclude-from-burger"><span><i class="_icon-r2-c12"></i></span><span>Services</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/support/technical-services/?source=nav" data-walid="GUIHeader" class="_nav-l3">Paid Project Support</a>
                                            <li><a href="http://www.wolfram.com/training/?source=nav" data-walid="GUIHeader" class="_nav-l3">Training</a>
                                            <li><a href="http://education.wolfram.com/summer/?source=nav" data-walid="GUIHeader" class="_nav-l3">Summer Programs</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                                <ul class="_nav-c4 hide__900">
                                    <li class="_nav-hover"><span class="mini _nav-l2"><span><i class="_icon-r2-c11"></i></span><span>Mobile Apps</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/player-app/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Player</a>
                                            <li><a href="http://www.wolfram.com/cloud-app/?source=nav" target="_blank" data-walid="GUIHeader" class="_nav-l3">Wolfram Cloud App</a>
                                            <li><a href="http://products.wolframalpha.com/mobile/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram|Alpha for Mobile</a>
                                            <li><a href="http://products.wolframalpha.com/mobile/?source=nav#wapowered" data-walid="GUIHeader" class="_nav-l3">Wolfram|Alpha-Powered Apps</a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover"><span class="mini _nav-l2"><span><i class="_icon-r2-c12"></i></span><span>Services</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/support/technical-services/?source=nav" data-walid="GUIHeader" class="_nav-l3">Paid Project Support</a>
                                            <li><a href="http://www.wolfram.com/training/?source=nav" data-walid="GUIHeader" class="_nav-l3">Training</a>
                                            <li><a href="http://education.wolfram.com/summer/?source=nav" data-walid="GUIHeader" class="_nav-l3">Summer Programs</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                            </div>
                        </div><!--/.table-->
                    </div>
                    <div class="_nav-footer font-size-3-4">
                        <a href="http://www.wolfram.com/products/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-has-line"><span><i class="_icon-r1-c6 hide show__600"></i></span><span class="chevron-after nothing-after__600 font-style-i__600">All Products &amp; Services</span></a>
                    </div>
                </div><!--/._nav-tab-content-->
            </div><!--/#_nav-products-->

            <div id="_nav-technologies" class="_nav-tab">
                <a href="http://www.wolfram.com/technologies/?source=nav" data-walid="GUIHeader" class="_nav-l1">Technologies<i class="_icon-r1-c1 hide__900"></i></a>
                <div class="_nav-tab-content">
                    <div class="_page-width padding-bt-1">
                        <div class="table width-full">
                            <div class="heirs-width-1-3">
                                <a href="http://www.wolfram.com/language/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c1"></i></span><span>Wolfram Language</span></span>
                                    <p>Revolutionary knowledge-based programming language.</p>
                                </a>
                                <a href="http://www.wolfram.com/cdf/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c2"></i></span><span>Computable Document Format</span></span>
                                    <p>Computation-powered interactive documents.</p>
                                </a>
                                <a href="http://www.wolfram.com/data-framework/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c3"></i></span><span>Wolfram Data Framework</span></span>
                                    <p>Semantic framework for real-world data.</p>
                                </a>
                            </div>
                            <div>
                                <a href="http://www.wolfram.com/cloud/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c4"></i></span><span>Wolfram Cloud</span></span>
                                    <p>Central infrastructure for Wolfram's cloud products &amp; services.</p>
                                </a>
                                <a href="http://www.wolfram.com/engine/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c5"></i></span><span>Wolfram Engine</span></span>
                                    <p>Software engine implementing the Wolfram Language.</p>
                                </a>
                                <a href="http://www.wolfram.com/universal-deployment-system/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c6"></i></span><span>Wolfram Universal Deployment System</span></span>
                                    <p>Instant deployment across cloud, desktop, mobile, and more.</p>
                                </a>
                            </div>
                            <div>
                                <a href="http://www.wolfram.com/wolfram-science/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c7"></i></span><span>Wolfram Science</span></span>
                                    <p>Technology-enabling science of the computational universe.</p>
                                </a>
                                <a href="http://www.wolfram.com/natural-language-understanding/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c8"></i></span><span>Wolfram Natural Language Understanding System</span></span>
                                    <p>Knowledge-based, broadly deployed natural language.</p>
                                </a>
                                <a href="http://www.wolfram.com/knowledgebase/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-hover">
                                    <span class="mini"><span><i class="_icon-r3-c9"></i></span><span>Wolfram Knowledgebase</span></span>
                                    <p>Curated computable knowledge powering Wolfram|Alpha.</p>
                                </a>
                            </div>
                        </div><!--/.table-->
                    </div>
                    <div class="_nav-footer font-size-3-4">
                        <a href="http://www.wolfram.com/technologies/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-has-line"><span><i class="_icon-r1-c6 hide show__600"></i></span><span class="chevron-after nothing-after__600 font-style-i__600">All Technologies</span></a>
                    </div>
                </div><!--/._nav-tab-content-->
            </div><!--/#_nav-technologies-->

            <div id="_nav-solutions" class="_nav-tab">
                <a href="http://www.wolfram.com/solutions/?source=nav" data-walid="GUIHeader" class="_nav-l1">Solutions<i class="_icon-r1-c1 hide__900"></i></a>
                <div class="_nav-tab-content">
                    <div class="_page-width padding-bt-1">
                        <div class="table width-full">
                            <div class="heirs-width-1-4">
                                <ul class="_nav-c1">
                                    <li class="_nav-hover"><span class="_nav-l2 mini"><span><i class="_icon-r4-c1"></i></span><span>Engineering, R&amp;D</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/solutions/industry/aerospace-engineering/?source=nav" data-walid="GUIHeader" class="_nav-l3">Aerospace &amp; Defense</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/chemical-engineering/?source=nav" data-walid="GUIHeader" class="_nav-l3">Chemical Engineering</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/control-systems/?source=nav" data-walid="GUIHeader" class="_nav-l3">Control Systems</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/electrical-engineering/?source=nav" data-walid="GUIHeader" class="_nav-l3">Electrical Engineering</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/image-processing/?source=nav" data-walid="GUIHeader" class="_nav-l3">Image Processing</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/industrial-engineering/?source=nav" data-walid="GUIHeader" class="_nav-l3">Industrial Engineering</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/mechanical-engineering/?source=nav" data-walid="GUIHeader" class="_nav-l3">Mechanical Engineering</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/operations-research/?source=nav" data-walid="GUIHeader" class="_nav-l3">Operations Research</a>
                                            <li><a href="http://www.wolfram.com/solutions/?source=nav" data-walid="GUIHeader" class="_nav-l3 font-style-i">More...</a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover hide show__900"><span class="mini _nav-l2 _exclude-from-burger"><span><i class="_icon-r2-c10"></i></span><span>Education</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/education/?source=nav" data-walid="GUIHeader" class="_nav-l3">All Solutions for Education</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                                <ul class="_nav-c2">
                                    <li class="_nav-hover"><span class="mini _nav-l2"><span><i class="_icon-r4-c3"></i></span><span>Finance, Statistics &amp; Business Analysis</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/solutions/industry/actuarial-sciences/?source=nav" data-walid="GUIHeader" class="_nav-l3">Actuarial Sciences</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/bioinformatics/?source=nav" data-walid="GUIHeader" class="_nav-l3">Bioinformatics</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/data-science/?source=nav" data-walid="GUIHeader" class="_nav-l3">Data Science</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/econometrics/?source=nav" data-walid="GUIHeader" class="_nav-l3">Econometrics</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/financial-risk-management/?source=nav" data-walid="GUIHeader" class="_nav-l3">Financial Risk Management</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/statistics/?source=nav" data-walid="GUIHeader" class="_nav-l3">Statistics</a>
                                            <li><a href="http://www.wolfram.com/solutions/?source=nav" data-walid="GUIHeader" class="_nav-l3 font-style-i">More...</a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover hide show__900"><span class="mini _nav-l2 _exclude-from-burger"><span><i class="_icon-r4-c2"></i></span><span>Web &amp; Software</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/solutions/industry/electronic-publishing/?source=nav" data-walid="GUIHeader" class="_nav-l3">Authoring &amp; Publishing</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/interface-development/?source=nav" data-walid="GUIHeader" class="_nav-l3">Interface Development</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/software-engineering/?source=nav" data-walid="GUIHeader" class="_nav-l3">Software Engineering</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/web-development/?source=nav" data-walid="GUIHeader" class="_nav-l3">Web Development</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                                <ul class="_nav-c3 border-r-n__900">
                                    <li class="_nav-hover hide__900"><span class="mini _nav-l2"><span><i class="_icon-r2-c10"></i></span><span>Education</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/education/?source=nav" data-walid="GUIHeader" class="_nav-l3">All Solutions for Education</a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover"><span class="mini _nav-l2"><span><i class="_icon-r4-c5"></i></span><span>Trends</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/featureset/machine-learning/?source=nav" data-walid="GUIHeader" class="_nav-l3">Machine Learning</a>
                                            <li><a href="http://www.mpdatascience.com/?source=nav" data-walid="GUIHeader" class="_nav-l3">Multiparadigm Data Science</a>
                                            <li><a href="http://www.wolfram.com/internet-of-things/?source=nav" data-walid="GUIHeader" class="_nav-l3">Internet of Things</a>
                                            <li><a href="http://www.wolfram.com/solutions/hpc/?source=nav" data-walid="GUIHeader" class="_nav-l3">High-Performance Computing</a>
                                            <li><a href="http://www.wolfram.com/hackathons/?source=nav" data-walid="GUIHeader" class="_nav-l3">Hackathons</a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover hide show__900"><span class="_nav-l2 mini _exclude-from-burger"><span><i class="_icon-r4-c4"></i></span><span>Sciences</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/solutions/industry/astronomy/?source=nav" data-walid="GUIHeader" class="_nav-l3">Astronomy</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/biological-sciences/?source=nav" data-walid="GUIHeader" class="_nav-l3">Biology</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/chemistry/?source=nav" data-walid="GUIHeader" class="_nav-l3">Chemistry</a>
                                            <li><a href="http://www.wolfram.com/solutions/?source=nav" data-walid="GUIHeader" class="_nav-l3 font-style-i">More...</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                                <ul class="_nav-c4 hide__900">
                                    <li class="_nav-hover"><span class="mini _nav-l2"><span><i class="_icon-r4-c2"></i></span><span>Web &amp; Software</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/solutions/industry/electronic-publishing/?source=nav" data-walid="GUIHeader" class="_nav-l3">Authoring &amp; Publishing</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/interface-development/?source=nav" data-walid="GUIHeader" class="_nav-l3">Interface Development</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/software-engineering/?source=nav" data-walid="GUIHeader" class="_nav-l3">Software Engineering</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/web-development/?source=nav" data-walid="GUIHeader" class="_nav-l3">Web Development</a>
                                        </ul>
                                    <!--</li>-->
                                    <li class="_nav-hover"><span class="_nav-l2 mini"><span><i class="_icon-r4-c4"></i></span><span>Sciences</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/solutions/industry/astronomy/?source=nav" data-walid="GUIHeader" class="_nav-l3">Astronomy</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/biological-sciences/?source=nav" data-walid="GUIHeader" class="_nav-l3">Biology</a>
                                            <li><a href="http://www.wolfram.com/solutions/industry/chemistry/?source=nav" data-walid="GUIHeader" class="_nav-l3">Chemistry</a>
                                            <li><a href="http://www.wolfram.com/solutions/?source=nav" data-walid="GUIHeader" class="_nav-l3 font-style-i">More...</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                            </div>
                        </div><!--/.table-->
                    </div>
                    <div class="_nav-footer font-size-3-4">
                        <a href="http://www.wolfram.com/solutions/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-has-line"><span><i class="_icon-r1-c6 hide show__600"></i></span><span class="chevron-after nothing-after__600 font-style-i__600">All Solutions</span></a>
                    </div>
                </div><!--/._nav-tab-content-->
            </div><!--/#_nav-solutions-->

            <div id="_nav-support" class="_nav-tab">
                <a href="http://www.wolfram.com/support/?source=nav" data-walid="GUIHeader" class="_nav-l1">Support<span class="hide__1200 display-i__600"> &amp; Learning</span><i class="_icon-r1-c1 hide__900"></i></a>
                <div class="_nav-tab-content">
                    <div class="_page-width padding-bt-1">
                        <div class="table width-full">
                            <div class="heirs-width-1-3__900">
                                <ul class="_nav-c1 _nav-hover width-1-2">
                                    <li class="grid heirs-width-1-2 heirs-width-full__900">
                                        <ul>
                                            <li><span class="mini _nav-l2"><span><i class="_icon-r5-c1"></i></span><span>Learning</span></span>
                                                <ul>
                                                    <li><a href="http://reference.wolfram.com/language/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Language Documentation</a>
                                                    <li><a href="http://www.wolfram.com/language/fast-introduction-for-programmers/?source=nav" data-walid="GUIHeader" class="_nav-l3">Fast Introduction for Programmers</a>
                                                    <li><a href="http://www.wolfram.com/training/?source=nav" data-walid="GUIHeader" class="_nav-l3">Training</a>
                                                    <li><a href="http://www.wolfram.com/broadcast/?source=nav" data-walid="GUIHeader" class="_nav-l3">Videos &amp; Screencasts</a>
                                                </ul>
                                            <!--</li>-->
                                        </ul>
                                        <ul class="display-tr__900">
                                            <li><span class="hide__900">&nbsp;</span>
                                                <ul>
                                                    <li><a href="http://www.wolfram.com/language/elementary-introduction/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Language Introductory Book</a>
                                                    <li><a href="http://www.wolfram.com/training/special-event/?source=nav" data-walid="GUIHeader" class="_nav-l3">Virtual Workshops</a>
                                                    <li><a href="http://education.wolfram.com/summer/?source=nav" data-walid="GUIHeader" class="_nav-l3">Summer Programs</a>
                                                    <li><a href="http://www.wolfram.com/books/?source=nav" data-walid="GUIHeader" class="_nav-l3">Books</a>
                                                </ul>
                                            <!--</li>-->
                                        </ul>
                                    <!--</li>-->
                                </ul>
                                <ul class="_nav-c2 _nav-hover width-1-4">
                                    <li><span class="mini _nav-l2"><span><i class="_icon-r5-c2"></i></span><span>Need Help?</span></span>
                                        <ul>
                                            <li><a href="http://support.wolfram.com/kb/?source=nav" data-walid="GUIHeader" class="_nav-l3">Support FAQ</a>
                                            <li><a href="http://community.wolfram.com/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Community</a>
                                            <li><a href="http://www.wolfram.com/support/contact/?source=nav" data-walid="GUIHeader" class="_nav-l3">Contact Support</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                                <ul class="_nav-c3 _nav-hover width-1-4">
                                    <li><span class="mini _nav-l2"><span><i class="_icon-r5-c3"></i></span><span>Premium Support</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/mathematica/pricing/premier-service.php?source=nav" data-walid="GUIHeader" class="_nav-l3">Premier Service</a>
                                            <li><a href="http://www.wolfram.com/support/technical-services/?source=nav" data-walid="GUIHeader" class="_nav-l3">Technical Services</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                            </div>
                        </div><!--/.table-->
                    </div>
                    <div class="_nav-footer font-size-3-4">
                        <a href="http://www.wolfram.com/support/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-has-line"><span><i class="_icon-r1-c6 hide show__600"></i></span><span class="chevron-after nothing-after__600 font-style-i__600">All Support &amp; Learning</span></a>
                    </div>
                </div><!--/._nav-tab-content-->
            </div><!--/#_nav-support-->

            <div id="_nav-company" class="_nav-tab">
                <a href="http://www.wolfram.com/company/?source=nav" data-walid="GUIHeader" class="_nav-l1">Company<i class="_icon-r1-c1 hide__900"></i></a>
                <div class="_nav-tab-content">
                    <div class="_page-width padding-bt-1">
                        <div class="table width-full">
                            <div class="heirs-width-1-3__900">
                                <ul class="_nav-c1 _nav-hover width-1-4">
                                    <li><span class="mini _nav-l2"><span><i class="_icon-r6-c1"></i></span><span>About</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/company/background.html?source=nav" data-walid="GUIHeader" class="_nav-l3">Company Background</a>
                                            <li><a href="http://blog.wolfram.com/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Blog</a>
                                            <li><a href="http://company.wolfram.com/announcements/?source=nav" data-walid="GUIHeader" class="_nav-l3">Announcements</a>
                                            <li><a href="http://company.wolfram.com/events/?source=nav" data-walid="GUIHeader" class="_nav-l3">Events</a>
                                            <li><a href="http://www.wolfram.com/company/contact/?source=nav" data-walid="GUIHeader" class="_nav-l3">Contact Us</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                                <ul class="_nav-c2 _nav-hover width-1-4">
                                    <li><span class="mini _nav-l2"><span><i class="_icon-r6-c2"></i></span><span>Work with Us</span></span>
                                        <ul>
                                            <li><a href="http://www.wolfram.com/company/careers/?source=nav" data-walid="GUIHeader" class="_nav-l3">Careers at Wolfram</a>
                                            <li><a href="http://www.wolfram.com/company/careers/?source=nav" data-walid="GUIHeader" class="_nav-l3">Internships</a>
                                            <li><a href="http://community.wolfram.com/content?curTag=jobs&amp;source=nav" data-walid="GUIHeader" class="_nav-l3">Other Wolfram Language Jobs</a>
                                        </ul>
                                    <!--</li>-->
                                </ul>
                                <ul class="_nav-c3 _nav-hover width-1-2">
                                    <li class="grid heirs-width-1-2 heirs-width-full__900">
                                        <ul>
                                            <li><span class="mini _nav-l2"><span><i class="_icon-r6-c3"></i></span><span>Initiatives</span></span>
                                                <ul>
                                                    <li><a href="http://www.wolframfoundation.org/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Foundation</a>
                                                    <li><a href="http://mathworld.wolfram.com/?source=nav" data-walid="GUIHeader" target="_blank" class="_nav-l3">MathWorld</a>
                                                    <li><a href="http://www.computerbasedmath.org/?source=nav" data-walid="GUIHeader" class="_nav-l3">Computer-Based Math</a>
                                                    <li><a href="http://www.wolframscience.com/?source=nav" data-walid="GUIHeader" class="_nav-l3 font-style-i">A New Kind of Science</a>
                                                    <li><a href="http://www.wolfram.com/hackathons/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Technology for Hackathons</a>
                                                    <li><a href="http://www.wolfram.com/company/careers/ambassador/?source=nav" data-walid="GUIHeader" class="_nav-l3">Student Ambassador Program</a>
                                                </ul>
                                            <!--</li>-->
                                        </ul>
                                        <ul class="display-tr__900">
                                            <li><span class="hide__900">&nbsp;</span>
                                                <ul>
                                                    <li><a href="http://www.wolfram.com/startups/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram for Startups</a>
                                                    <li><a href="http://demonstrations.wolfram.com/?source=nav" data-walid="GUIHeader" class="_nav-l3">Demonstrations Project</a>
                                                    <li><a href="http://www.wolfram.com/events/technology-conference/innovator-award/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram Innovator Awards</a>
                                                    <li><a href="http://www.wolfram.com/raspberry-pi/?source=nav" data-walid="GUIHeader" class="_nav-l3">Wolfram + Raspberry Pi</a>
                                                    <li><a href="http://education.wolfram.com/summer/?source=nav" data-walid="GUIHeader" class="_nav-l3">Summer Programs</a>
                                                    <li><a href="http://www.wolfram.com/resources/?source=nav" data-walid="GUIHeader" class="_nav-l3 font-style-i">More...</a>
                                                </ul>
                                            <!--</li>-->
                                        </ul>
                                    <!--</li>-->
                                </ul>
                            </div>
                        </div><!--/.table-->
                    </div>
                    <div class="_nav-footer font-size-3-4">
                        <a href="http://www.wolfram.com/company/?source=nav" data-walid="GUIHeader" class="_nav-l2 _nav-has-line"><span><i class="_icon-r1-c6 hide show__600"></i></span><span class="chevron-after nothing-after__600 font-style-i__600">All Company</span></a>
                    </div>
                </div><!--/._nav-tab-content-->
            </div><!--/#_nav-company-->

            <div id="_nav-search" class="_nav-tab">
                <a href="//search.wolfram.com/?source=nav" data-walid="GUIHeader" class="_nav-l1"><i class="_icon-r1-c4 hide show__600"></i><i class="_icon-r1-c3 hide__600"></i><span class="hide__1200">Search</span></a>
                <ul class="_nav-tab-content">
                    <li id="_search-wrapper" class="cf">
                        <form action="//search.wolfram.com/" method="get" accept-charset="utf-8" class="no-bfc">
                            <div><input type="text" name="query" value="What are you looking for?" autocomplete="off" id="_search-input"></div>
                            <input type="hidden" name="source" value="GUIHeader">
                        </form>
                    <!--</li>-->
                </ul><!--/._nav-tab-content-->
            </div><!--/#_nav-search-->

            <div id="_nav-burger" class="_nav-tab hide show__600">
                <a href="http://www.wolfram.com/site-map/?source=nav" data-walid="GUIHeader" class="_nav-l1"><i class="_icon-r1-c5"></i></a>
                <div class="_nav-tab-content font-size-1-1-8">
                </div><!--/._nav-tab-content-->
            </div><!--/#_nav-burger-->

        </nav><!--/#_nav-->
    </div><!--/#_header-b-->
</header><!--/#_header-->

<!-- end framework header en -->


<main class="main">
<header class="header">
    <div class="inner">
        <a href="/language" class="header-link">
            <span class="heading1">Wolfram Language &amp; System</span>
            <span class="heading2">Documentation Center</span>
        </a>
        <div class="right">
            <form class="search" method="get" name="searchpageform" action="/search/" id="ref-search-form">
                <input type="submit" value="q" id="search-button"><input id="query" name="query" type="text" value="" placeholder="Search"><button class="clearfield"></button>
            </form>
            <a class="language-home" href="http://www.wolfram.com/language">Wolfram Language Home Page&nbsp;&raquo;</a>
        </div>
    </div>
    
</header>
  <div class="inner main-content"><nav class="topContentWrap"><span class="badge">BUILT-IN SYMBOL</span><ul class="dropdown">
   <li>
    <a href="#" class="menu see-also">See Also</a>
    <ul class="sub_menu">
     <li>
      <a href="/language/ref/RollPitchYawMatrix.html"><span class="dropdownPad">RollPitchYawMatrix</span></a>
     </li>
     <li>
      <a href="/language/ref/EulerAngles.html"><span class="dropdownPad">EulerAngles</span></a>
     </li>
     <li>
      <a href="/language/ref/EulerMatrix.html"><span class="dropdownPad">EulerMatrix</span></a>
     </li>
     <li>
      <a href="/language/ref/RotationMatrix.html"><span class="dropdownPad">RotationMatrix</span></a>
     </li>
     <li>
      <a href="/language/ref/RotationTransform.html"><span class="dropdownPad">RotationTransform</span></a>
     </li>
    </ul>
   </li>
   <li>
    <a href="#" class="menu related-guides">Related Guides</a>
    <ul class="sub_menu">
     <li>
      <a href="/language/guide/GeometricTransforms.html"><span class="dropdownPad">Geometric Transforms</span></a>
     </li>
    </ul>
   </li>
  </ul></nav><div class="main-heading"><h1 class="main-title">RollPitchYawAngles</h1><div class="iconography" data-src="s= d= m= c= u= l= n= e="></div></div><div class="functionIntroWrap">
  <div class="functionIntro">
   <p class="code">
    <span class="IF"><a href="/language/ref/RollPitchYawAngles.html">RollPitchYawAngles</a><span class="openbracket">[</span><span class="TI">r</span><span class="closebracket">]</span></span>
   </p>
   <p class="code-description">gives the roll-pitch-yaw angles <span class="IF"><span class="openbrace">{</span><span class="TR"><span class="special-character Alpha">&#945;</span></span><span class="comma">,</span><span class="TR"><span class="special-character Beta">&#946;</span></span><span class="comma">,</span><span class="TR"><span class="special-character Gamma">&#947;</span></span><span class="closebrace">}</span></span> corresponding to the rotation matrix <span class="IF"><span class="TI">r</span></span>.</p>
  </div>
  <div class="functionIntro">
   <p class="code">
    <span class="IF"><a href="/language/ref/RollPitchYawAngles.html">RollPitchYawAngles</a><span class="openbracket">[</span><span class="TI">r</span><span class="comma">,</span><span class="openbrace">{</span><span class="TI">a</span><span class="comma">,</span><span class="TI">b</span><span class="comma">,</span><span class="TI">c</span><span class="closebrace">}</span><span class="closebracket">]</span></span>
   </p>
   <p class="code-description">gives the roll-pitch-yaw angles <span class="IF"><span class="openbrace">{</span><span class="TR"><span class="special-character Alpha">&#945;</span></span><span class="comma">,</span><span class="TR"><span class="special-character Beta">&#946;</span></span><span class="comma">,</span><span class="TR"><span class="special-character Gamma">&#947;</span></span><span class="closebrace">}</span></span> corresponding to rotation order <span class="IF"><span class="openbrace">{</span><span class="TI">a</span><span class="comma">,</span><span class="TI">b</span><span class="comma">,</span><span class="TI">c</span><span class="closebrace">}</span></span>.</p>
  </div>
 </div><section id="DetailsAndOptions"><h1 class="toggle">Details</h1><div class="NotesThumbnails">
   <img src="Files/RollPitchYawAngles.en/details_1.png"
       height="70"
       width="170"
       alt="" />
   <img src="Files/RollPitchYawAngles.en/details_2.png"
       height="70"
       width="170"
       alt="" />
   <img src="Files/RollPitchYawAngles.en/details_3.png"
       height="70"
       width="170"
       alt="" />
  </div><div class="hideable">
   <ul class="functionList">
    <li><a name="279907394"></a><span class="IF"><a href="/language/ref/RollPitchYawAngles.html">RollPitchYawAngles</a></span> is used to decompose into fixed axis-oriented rotations.</li>
    <li><a name="198658159"></a><span class="IF"><a href="/language/ref/RollPitchYawAngles.html">RollPitchYawAngles</a><span class="openbracket">[</span><span class="TI">r</span><span class="comma">,</span><span class="openbrace">{</span><span class="TI">a</span><span class="comma">,</span><span class="TI">b</span><span class="comma">,</span><span class="TI">c</span><span class="closebrace">}</span><span class="closebracket">]</span></span> gives angles <span class="IF"><span class="openbrace">{</span><span class="TR"><span class="special-character Alpha">&#945;</span></span><span class="comma">,</span><span class="TR"><span class="special-character Beta">&#946;</span></span><span class="comma">,</span><span class="TR"><span class="special-character Gamma">&#947;</span></span><span class="closebrace">}</span></span> such that <span class="IF"><a href="/language/ref/RollPitchYawMatrix.html">RollPitchYawMatrix</a><span class="openbracket">[</span><span class="openbrace">{</span><span class="TR"><span class="special-character Alpha">&#945;</span></span><span class="comma">,</span><span class="TR"><span class="special-character Beta">&#946;</span></span><span class="comma">,</span><span class="TR"><span class="special-character Gamma">&#947;</span></span><span class="closebrace">}</span><span class="comma">,</span><span class="openbrace">{</span><span class="TI">a</span><span class="comma">,</span><span class="TI">b</span><span class="comma">,</span><span class="TI">c</span><span class="closebrace">}</span><span class="closebracket">]</span><span class="special-character Equal">&#62513;</span><span class="TI">r</span></span>.</li>
    <li><a name="551919935"></a><span class="IF"><a href="/language/ref/RollPitchYawAngles.html">RollPitchYawAngles</a><span class="openbracket">[</span>r<span class="closebracket">]</span></span> is equivalent to <span class="IF"><a href="/language/ref/RollPitchYawAngles.html">RollPitchYawAngles</a><span class="openbracket">[</span>r<span class="comma">,</span><span class="openbrace">{</span>3<span class="comma">,</span>2<span class="comma">,</span>1<span class="closebrace">}</span><span class="closebracket">]</span></span>, the z-y-x rotation.</li>
    <li><a name="587873956"></a>The default z-y-x angles <span class="IF"><a href="/language/ref/RollPitchYawAngles.html">RollPitchYawAngles</a><span class="openbracket">[</span><span class="TI">r</span><span class="comma">,</span><span class="openbrace">{</span>3<span class="comma">,</span>2<span class="comma">,</span>1<span class="closebrace">}</span><span class="closebracket">]</span></span> decompose rotation into three steps:</li>
    <img src="Files/RollPitchYawAngles.en/Image_1.gif"
        height="122"
        width="507"
        class=""
        alt="" />
    <li><a name="540861325"></a>The rotation axes <span class="IF"><span class="TI">a</span></span>, <span class="IF"><span class="TI">b</span></span>, and <span class="IF"><span class="TI">c</span></span> can be any integer <span class="IF">1</span>, <span class="IF">2</span>, or <span class="IF">3</span>, but there are only twelve combinations that are general enough to be able to specify any 3D rotation. </li>
    <li><a name="325742727"></a>Rotations with the first and last axis repeated: </li>
    <li class="NotesTable">
     <a name="842343443"></a>
     <table>
      <col width="1%" />
      <col width="28%" />
      <col width="28%" />
      <col width="43%" />
      <tr class="lineAbove" style=""><td /><td><span class="openbrace">{</span>3<span class="comma">,</span>2<span class="comma">,</span>3<span class="closebrace">}</span></td><td><span class="TT">z-y-z rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/2.gif" height="48" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/3.gif" height="43" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/4.gif" height="45" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>3<span class="comma">,</span>1<span class="comma">,</span>3<span class="closebrace">}</span></td><td><span class="TT">z-x-z rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/5.gif" height="48" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/6.gif" height="45" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/7.gif" height="47" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>2<span class="comma">,</span>3<span class="comma">,</span>2<span class="closebrace">}</span></td><td><span class="TT">y-z-y rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/8.gif" height="43" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/9.gif" height="44" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/10.gif" height="41" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>2<span class="comma">,</span>1<span class="comma">,</span>2<span class="closebrace">}</span></td><td><span class="TT">y-x-y rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/11.gif" height="43" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/12.gif" height="42" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/13.gif" height="42" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>1<span class="comma">,</span>3<span class="comma">,</span>1<span class="closebrace">}</span></td><td><span class="TT">x-z-x rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/14.gif" height="44" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/15.gif" height="45" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/16.gif" height="49" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>1<span class="comma">,</span>2<span class="comma">,</span>1<span class="closebrace">}</span></td><td><span class="TT">x-y-x rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/17.gif" height="44" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/18.gif" height="42" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/19.gif" height="45" width="61" alt="" /></span></td></tr>
     </table>
    </li>
    <li><a name="26445803"></a>Rotations with all three axes different: </li>
    <li class="NotesTable">
     <a name="1054045477"></a>
     <table>
      <col width="1%" />
      <col width="28%" />
      <col width="28%" />
      <col width="43%" />
      <tr class="lineAbove" style=""><td /><td><span class="openbrace">{</span>1<span class="comma">,</span>2<span class="comma">,</span>3<span class="closebrace">}</span></td><td><span class="TT">x-y-z rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/20.gif" height="44" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/21.gif" height="42" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/22.gif" height="44" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>1<span class="comma">,</span>3<span class="comma">,</span>2<span class="closebrace">}</span></td><td><span class="TT">x-z-y rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/23.gif" height="44" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/24.gif" height="45" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/25.gif" height="44" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>2<span class="comma">,</span>1<span class="comma">,</span>3<span class="closebrace">}</span></td><td><span class="TT">y-x-z rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/26.gif" height="43" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/27.gif" height="42" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/28.gif" height="46" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>2<span class="comma">,</span>3<span class="comma">,</span>1<span class="closebrace">}</span></td><td><span class="TT">y-z-x rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/29.gif" height="43" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/30.gif" height="44" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/31.gif" height="44" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>3<span class="comma">,</span>1<span class="comma">,</span>2<span class="closebrace">}</span></td><td><span class="TT">z-x-y rotation</span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/32.gif" height="48" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/33.gif" height="45" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/34.gif" height="45" width="61" alt="" /></span></td></tr>
      <tr class="" style=""><td /><td><span class="openbrace">{</span>3<span class="comma">,</span>2<span class="comma">,</span>1<span class="closebrace">}</span></td><td><span class="TT"><span class="specialcharacters">z-y-x rotation <span class="openparenthesis">(</span>default<span class="closeparenthesis">)</span></span></span></td><td><span class="TT"><img src="Files/RollPitchYawAngles.en/35.gif" height="48" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/36.gif" height="43" width="61" alt="" /><img src="Files/RollPitchYawAngles.en/37.gif" height="47" width="61" alt="" /></span></td></tr>
     </table>
    </li>
    <li><a name="311450916"></a>Rotations with subsequent axes repeated may not be invertible since these are not capable of representing all possible rotations in 3D.</li>
   </ul>
  </div></section><section id="Examples"><h1 class="toggle open">Examples</h1><span class="open-all on">open all</span><span class="close-all">close all</span><div class="hideable">
   <div>
    <h2 class="toggle open">Basic Examples<span class="special-character NonBreakingSpace">&#160;</span><span class="special-character NonBreakingSpace">&#160;</span><span class="total-examples">(2)</span></h2>
    <div class="hideable">
     <p><a name="1242291035"></a>Get roll-pitch-yaw angles from the rotation matrix:</p>
     <table class="InCell">
      <tr><td class="lab">In[1]:=</td><td class="Input"><div>
         <a name="2075319587"></a>
         <img src="Files/RollPitchYawAngles.en/I_2.png"
             height="19"
             width="246"
             alt="Click for copyable input" />
        </div><div id="i_1_out" class="IFL"></div></td></tr>
     </table>
     <div class="IO">
      <table class="InCell">
       <tr><td class="lab">In[2]:=</td><td class="Input"><div>
          <a name="414031176"></a>
          <img src="Files/RollPitchYawAngles.en/I_4.png"
              height="19"
              width="144"
              alt="Click for copyable input" />
         </div><div id="i_3_out" class="IFL"></div></td></tr>
      </table>
      <table class="OCell">
       <tr><td class="lab">Out[2]=</td><td class="Output"><div class="output-image">
          <img src="Files/RollPitchYawAngles.en/O_1.png"
              height="29"
              width="58"
              alt="" />
         </div></td></tr>
      </table>
     </div>
     <div class="ExLine"><a name="624480190"></a><!-- --></div>
     <p><a name="1672577136"></a>Get roll-pitch-yaw angles from the rotation matrix with the given rotation order:</p>
     <table class="InCell">
      <tr><td class="lab">In[1]:=</td><td class="Input"><div>
         <a name="442985522"></a>
         <img src="Files/RollPitchYawAngles.en/I_6.png"
             height="19"
             width="321"
             alt="Click for copyable input" />
        </div><div id="i_5_out" class="IFL"></div></td></tr>
     </table>
     <div class="IO">
      <table class="InCell">
       <tr><td class="lab">In[2]:=</td><td class="Input"><div>
          <a name="2079347752"></a>
          <img src="Files/RollPitchYawAngles.en/I_8.png"
              height="19"
              width="199"
              alt="Click for copyable input" />
         </div><div id="i_7_out" class="IFL"></div></td></tr>
      </table>
      <table class="OCell">
       <tr><td class="lab">Out[2]=</td><td class="Output"><div class="output-image">
          <img src="Files/RollPitchYawAngles.en/O_2.png"
              height="29"
              width="64"
              alt="" />
         </div></td></tr>
      </table>
     </div>
    </div>
   </div>
   <div>
    <h2 class="toggle load">Scope<span class="special-character NonBreakingSpace">&#160;</span><span class="special-character NonBreakingSpace">&#160;</span><span class="total-examples">(2)</span></h2>
    <div class="hideable"></div>
   </div>
   <div>
    <h2 class="toggle load">Properties &amp; Relations<span class="special-character NonBreakingSpace">&#160;</span><span class="special-character NonBreakingSpace">&#160;</span><span class="total-examples">(1)</span></h2>
    <div class="hideable"></div>
   </div>
   <div>
    <h2 class="toggle load">Possible Issues<span class="special-character NonBreakingSpace">&#160;</span><span class="special-character NonBreakingSpace">&#160;</span><span class="total-examples">(1)</span></h2>
    <div class="hideable"></div>
   </div>
   <div class="clear"><!-- --></div>
  </div></section><section id="SeeAlso"><h1>See Also</h1><p class="inlineFunctionList"><span class="IF"><a href="/language/ref/RollPitchYawMatrix.html">RollPitchYawMatrix</a></span><span class="special-character NonBreakingSpace">&#160;</span><span class="inlineSeparator"></span> <span class="IF"><a href="/language/ref/EulerAngles.html">EulerAngles</a></span><span class="special-character NonBreakingSpace">&#160;</span><span class="inlineSeparator"></span> <span class="IF"><a href="/language/ref/EulerMatrix.html">EulerMatrix</a></span><span class="special-character NonBreakingSpace">&#160;</span><span class="inlineSeparator"></span> <span class="IF"><a href="/language/ref/RotationMatrix.html">RotationMatrix</a></span><span class="special-character NonBreakingSpace">&#160;</span><span class="inlineSeparator"></span> <span class="IF"><a href="/language/ref/RotationTransform.html">RotationTransform</a></span></p></section><section id="RelatedGuides"><h1>Related Guides</h1><ul class="functionList">
   <li>
    <a name="329014674"></a>
    <a href="/language/guide/GeometricTransforms.html">Geometric Transforms</a>
   </li>
  </ul></section><div class="modified">Introduced in 2015<div class="history-version"> (10.2)</div></div>
  <section class="feedback-wrapper">
<div class="feedback-content">
    <button class="feedback"><span class="give">Give</span> Feedback</button><a class="toplink" href="#top"><span class="top">Top</span></a>
    <form id="feedbackForm" class="feedback-form" action="" method="post">
    <input type="hidden" value="submit" name="action" />
    <input type="hidden" value="" id="referer" name="referer" />
    <div id="thank_you" class="hide">
        <span class="feedback-form-heading">Thank you for your feedback! </span>
    </div>
    <table id="formTable">
        <tr>
            <td colspan="2" id="feedbackMessageTable" class="message">
                <p><label class="feedback-form-heading">Documentation Feedback</label></p>
                <p id="feedbackNotSent" class="errorbox hide">Oops. An error occurred. Please try again later.<br><small>If you continue to experience a problem or if you have any questions, please <a href="http://www.wolfram.com/support/contact/email/">contact us</a>.</small></p>
                <textarea id="feedbackMessage" name="feedbackMessage" rows="4" cols="50"></textarea>
                <label class="errorbox hide" for="feedbackMessage">Please complete this field.</label>
            </td>
        </tr>
        <tr>
            <td class="name">
                <label class="name text" for="name">Name <span class="optional">(optional)</span></label>
                <input type="text" class="text" name="name" id="name" value="" />
            </td>
            <td class="email">
                <label class="email text" for="email">Email address <span class="optional">(optional)</span></label>
                <input type="email" class="text" name="email" id="email" value="" />
            </td>
        </tr>
        <tr>
            <td colspan="2">
                <input type="submit" id="submit" class="button" value="Send Feedback">
            </td>
        </tr>
    </table>
    </form>
</div>
</section>
</div>
  </main>
<div id="_footer-offset"></div>
<footer class="footer-links">
  <div class="inner">
    <div class="footer-main-links">
      <a class="icon fast-intro" href="https://www.wolfram.com/language/fast-introduction-for-programmers/en/">
        Introduction for Programmers
      </a>
      <div class="nowrap"><a class="icon elementary-intro" target="_blank" href="https://www.wolfram.com/language/elementary-introduction/">Introductory Book</a></div>
    </div>
    <div class="footer-secondary-links">
      <a class="data-repo" target="_blank" href="https://datarepository.wolframcloud.com/">
        Wolfram Data Repository
      </a>
      <span class="divider">|</span>
      <a href="https://datadrop.wolframcloud.com/">
        Wolfram Data Drop
      </a>
      <span class="divider">|</span>
      <a href="https://www.wolfram.com/products/">
        Wolfram Language Products
      </a>
    </div>
    <a class="toplink" href="#top"><span class="top">Top</span></a>
  </div>
</footer>

<!-- begin framework footer en -->

<footer id="_footer" class="font-size-7-8 line-height-1-1-4">
    <nav id="_footer-t" class="_page-width grid padding-bt-2 heirs-width-1-5 heirs-width-1-4__900">
        <div class="hide__600">
            <ul>
                <li class="font-size-1">Products
                <li><a href="http://www.wolfram.com/wolfram-one/?source=footer" data-walid="GUIFooter">Wolfram|One</a>
                <li><a href="http://www.wolfram.com/mathematica/?source=footer" data-walid="GUIFooter">Mathematica</a>
                <li><a href="http://www.wolfram.com/development-platform/?source=footer" data-walid="GUIFooter">Development Platform</a>
                <li><a href="http://www.wolfram.com/programming-lab/?source=footer" data-walid="GUIFooter">Programming Lab</a>
                <li><a href="http://www.wolfram.com/data-science-platform/?source=footer" data-walid="GUIFooter">Data Science Platform</a>
                <li><a href="http://www.wolframalpha.com/pro/?source=footer" data-walid="GUIFooter">Wolfram|Alpha Pro</a>
                <li><a href="http://www.wolfram.com/products/?source=footer#mobile-apps" data-walid="GUIFooter">Mobile Apps</a>
                <li><a href="http://www.wolfram.com/finance-platform/?source=footer" data-walid="GUIFooter">Finance Platform</a>
                <li><a href="http://www.wolfram.com/system-modeler/?source=footer" data-walid="GUIFooter">SystemModeler</a>
                <li><a href="http://www.wolfram.com/products/workbench/?source=footer" data-walid="GUIFooter">Wolfram Workbench</a>
                <li><a href="http://www.wolfram.com/cdf-player/?source=footer" data-walid="GUIFooter">CDF Player</a>
                <li><a href="http://www.wolfram.com/group-organization-licensing/?source=footer" data-walid="GUIFooter">Volume &amp; Site Licensing</a>
                <li><a href="http://www.wolfram.com/enterprise-private-cloud/?source=footer" data-walid="GUIFooter">Enterprise Private Cloud</a>
                <li class="font-size-5-8 _footer-all"><a href="http://www.wolfram.com/products/?source=footer" data-walid="GUIFooter">View all...</a>
            </ul>
            <ul class="hide show__900">
                <li class="font-size-1">Services
                <li><a href="http://www.wolfram.com/support/technical-services/?source=footer" data-walid="GUIFooter">Technical Services</a>
                <li><a href="http://www.wolframsolutions.com/?source=footer" data-walid="GUIFooter">Corporate Consulting</a>
            </ul>
        </div>
        <div class="hide__600">
            <ul class="hide__900">
                <li class="font-size-1">Services
                <li><a href="http://www.wolfram.com/support/technical-services/?source=footer" data-walid="GUIFooter">Technical Services</a>
                <li><a href="http://www.wolframsolutions.com/?source=footer" data-walid="GUIFooter">Corporate Consulting</a>
            </ul>
            <ul>
                <li class="font-size-1">For Customers
                <li><a href="http://store.wolfram.com/?source=footer" data-walid="GUIFooter">Online Store</a>
                <li><a href="https://user.wolfram.com/portal/ProductRegistration?source=footer" data-walid="GUIFooter">Product Registration</a>
                <li><a href="https://user.wolfram.com/portal/login.html?source=footer" data-walid="GUIFooter">Product Downloads</a>
                <li><a href="https://user.wolfram.com/portal/login.html?source=footer" data-walid="GUIFooter">Service Plans Benefits</a>
            </ul>
            <ul class="hide__900">
                <li class="font-size-1">Support
                <li><a href="http://support.wolfram.com/kb/?source=footer" data-walid="GUIFooter">Support FAQ</a>
                <li><a href="http://www.wolfram.com/support/contact/email/?source=footer" data-walid="GUIFooter">Customer Service</a>
                <li><a href="http://www.wolfram.com/support/contact/?source=footer" data-walid="GUIFooter">Contact Support</a>
            </ul>
            <ul class="hide show__900">
                <li class="font-size-1">Public Resources
                <li><a href="http://www.wolframalpha.com/?source=footer" data-walid="GUIFooter">Wolfram|Alpha</a>
                <li><a href="http://demonstrations.wolfram.com/?source=footer" data-walid="GUIFooter">Demonstrations Project</a>
                <li><a href="http://devices.wolfram.com/?source=footer" data-walid="GUIFooter">Connected Devices Project</a>
                <li><a href="https://datadrop.wolframcloud.com/?source=footer" data-walid="GUIFooter">Wolfram Data Drop</a>
                <li><a href="http://www.wolfram.com/raspberry-pi/?source=footer" data-walid="GUIFooter">Wolfram + Raspberry Pi</a>
                <li><a href="http://www.wolframscience.com/?source=footer" data-walid="GUIFooter">Wolfram Science</a>
                <li><a href="http://www.computerbasedmath.org/?source=footer" data-walid="GUIFooter">Computer-Based Math</a>
                <li><a href="http://mathworld.wolfram.com/?source=footer" data-walid="GUIFooter" target="_blank">MathWorld</a>
                <li><a href="http://www.wolfram.com/hackathons/?source=footer" data-walid="GUIFooter">Hackathons</a>
                <li><a href="http://www.wolfram.com/resources/computational-thinking/?source=footer" data-walid="GUIFooter">Computational Thinking</a>
                <li class="font-size-5-8 _footer-all"><a href="http://www.wolfram.com/resources/?source=footer" data-walid="GUIFooter">View all...</a>
            </ul>
        </div>
        <div class="hide__600">
            <ul class="hide show__900">
                <li class="font-size-1">Support
                <li><a href="http://support.wolfram.com/kb/?source=footer" data-walid="GUIFooter">Support FAQ</a>
                <li><a href="http://www.wolfram.com/support/contact/email/?source=footer" data-walid="GUIFooter">Customer Service</a>
                <li><a href="http://www.wolfram.com/support/contact/?source=footer" data-walid="GUIFooter">Contact Support</a>
            </ul>
            <ul>
                <li class="font-size-1">Learning
                <li><a href="http://reference.wolfram.com/language/?source=footer" data-walid="GUIFooter">Wolfram Language Documentation</a>
                <li><a href="http://www.wolfram.com/language/elementary-introduction/?source=footer" data-walid="GUIFooter">Wolfram Language Introductory Book</a>
                <li><a href="http://www.wolfram.com/language/fast-introduction-for-programmers/?source=footer" data-walid="GUIFooter">Fast Introduction for Programmers</a>
                <li><a href="http://www.wolfram.com/language/fast-introduction-for-math-students/?source=footer" data-walid="GUIFooter">Fast Introduction for Math Students</a>
                <li><a href="http://www.wolfram.com/training/special-event/?source=footer" data-walid="GUIFooter">Virtual Workshops</a>
                <li><a href="http://www.wolfram.com/training/?source=footer" data-walid="GUIFooter">Training</a>
                <li><a href="http://education.wolfram.com/summer/?source=footer" data-walid="GUIFooter">Summer Programs</a>
                <li><a href="http://www.wolfram.com/broadcast/?source=footer" data-walid="GUIFooter">Videos</a>
                <li><a href="http://www.wolfram.com/books/?source=footer" data-walid="GUIFooter">Books</a>
            </ul>
        </div>
        <div class="hide__600">
            <ul class="hide__900">
                <li class="font-size-1">Public Resources
                <li><a href="http://www.wolframalpha.com/?source=footer" data-walid="GUIFooter">Wolfram|Alpha</a>
                <li><a href="http://demonstrations.wolfram.com/?source=footer" data-walid="GUIFooter">Demonstrations Project</a>
                <li><a href="http://devices.wolfram.com/?source=footer" data-walid="GUIFooter">Connected Devices Project</a>
                <li><a href="https://datadrop.wolframcloud.com/?source=footer" data-walid="GUIFooter">Wolfram Data Drop</a>
                <li><a href="http://www.wolfram.com/raspberry-pi/?source=footer" data-walid="GUIFooter">Wolfram + Raspberry Pi</a>
                <li><a href="http://www.wolframscience.com/?source=footer" data-walid="GUIFooter">Wolfram Science</a>
                <li><a href="http://www.computerbasedmath.org/?source=footer" data-walid="GUIFooter">Computer-Based Math</a>
                <li><a href="http://mathworld.wolfram.com/?source=footer" data-walid="GUIFooter" target="_blank">MathWorld</a>
                <li><a href="http://www.wolfram.com/hackathons/?source=footer" data-walid="GUIFooter">Hackathons</a>
                <li><a href="http://www.wolfram.com/resources/computational-thinking/?source=footer" data-walid="GUIFooter">Computational Thinking</a>
                <li class="font-size-5-8 _footer-all"><a href="http://www.wolfram.com/resources/?source=footer" data-walid="GUIFooter">View all...</a>
            </ul>
        </div>
        <div class="width-full__600">
            <ul class="hide__600">
                <li class="font-size-1">Company
                <li><a href="http://company.wolfram.com/announcements/?source=footer" data-walid="GUIFooter">Announcements</a>
                <li><a href="http://company.wolfram.com/events/?source=footer" data-walid="GUIFooter">Events</a>
                <li><a href="http://www.wolfram.com/company/background.html?source=footer" data-walid="GUIFooter">About Wolfram</a>
                <li><a href="http://www.wolfram.com/company/careers/?source=footer" data-walid="GUIFooter">Careers</a>
                <li><a href="http://www.wolfram.com/company/contact/?source=footer" data-walid="GUIFooter">Contact</a>
            </ul>
            <ul id="_footer-connect" class="text-align-c__600 heirs-padding-lr-1-2__600">
                <li class="font-size-1 hide__600">Connect
                <li class="display-ib__600"><a href="http://community.wolfram.com/?source=footer" data-walid="GUIFooter">Wolfram Community</a>
                <li class="display-ib__600"><a href="http://blog.wolfram.com/?source=footer" data-walid="GUIFooter">Wolfram Blog</a>
                <li class="display-ib__600"><a href="http://company.wolfram.com/announcements/newsletter/?source=footer" data-walid="GUIFooter">Newsletter</a>
                <li class="_footer-social margin-t-1-4 display-b__600"><a href="http://www.wolfram.com/connect/?source=footer" data-walid="GUIFooter"><i class="_icon-r7-c1 display-ib__600"></i></a>
            </ul>
        </div>
    </nav><!--/#_footer-t-->
    <div id="_footer-b" class="_page-width padding-t-1">
        <div class="grid collapse__600 heirs-width-a__600 heirs-center__600 heirs-text-align-c__600">
            <div id="_footer-bl" class="width-2-5">
                <span>© <span id="_footer-year">2019</span> <a href="http://www.wolfram.com/?source=footer">Wolfram</a>. All rights reserved.</span>
            </div>
            <div id="_footer-br" class="text-align-r width-3-5">
                <ul class="heirs-bar-between heirs-display-ib">
                    <li><a href="http://www.wolfram.com/legal/?source=footer" data-walid="GUIFooter">Legal</a>
                    <li><a href="http://www.wolfram.com/site-map/?source=footer" data-walid="GUIFooter">Site Map</a>
                    <li><a href="http://www.wolframalpha.com/?source=footer" data-walid="GUIFooter">WolframAlpha.com</a>
                    <li><a href="https://www.wolframcloud.com/?source=footer" data-walid="GUIFooter">WolframCloud.com</a>
                </ul>
            </div>
        </div>
        <div id="_footer-bc" class="padding-t-1 text-align-r text-align-c__600"></div>
    </div><!--/#_footer-b-->
</footer><!--/#_footer-->

<div id="_language-picker" class="hide margin-t-1__600">
    <i class="_icon-r7-c2"></i>
    <form id="_language-picker-form" class="no-bfc">
        <select id="_language-picker-select">
            <option disabled selected>Translate this page</option>
            <option value="/language/ref/RollPitchYawAngles.html.ja?source=footer">日本語</option>
            <option value="/language/ref/RollPitchYawAngles.html.zh?source=footer">中文</option>
        </select>
    </form>
</div>


<noscript id="_noscript" class="font-size-7-8 remove__ready">
    <div>
        <p><i></i>Enable JavaScript to interact with content and submit forms on Wolfram websites. <a href="http://www.enable-javascript.com/" target="_blank" data-walid="GUIFooter" class="chevron-after">Learn how</a></p>
    </div>
</noscript>
<script src="/common/framework/js/body.en.js"></script>

<!-- end framework footer en -->


    <script src="/language-assets/js/clipboard.js"></script>    
    <script src="/language-assets/js/language-specific.js.en"></script>
    <script src="/language-assets/js/global.js"></script>
    <script src="/language-assets/js/toggles.js"></script>
    <script src="/language-assets/js/workflows.js"></script>
    <script src="/language-assets/js/language.js"></script>
    <script src="/language-assets/js/dropdowns.js"></script>
    <script src="/language-assets/js/temporary.js"></script>
</body>
</html>
