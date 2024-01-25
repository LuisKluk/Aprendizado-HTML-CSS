<script setup>
import svg from "@/assets/teste.svg";
import iconloop from "@/assets/icon-loop.svg";
import iconsegurity from "@/assets/icon-segurity.svg";
import iconcloud from "@/assets/icon-cloud.svg";
import iconclock from "@/assets/icon-timeclock.svg";
import icontimemoney from "@/assets/icon-timemoney.svg";
import iconpapel from "@/assets/icon-papel.svg";
import iconpapers from "@/assets/icon-papers.svg";
import iconheadset from "@/assets/icon-headset.svg";
</script>
<template>
  <div>
    <div>
      <div class="banner">
        <img
          style="height: 25px"
          src="https://about.gitlab.com/_nuxt/image/eecfc0.svg"
          alt="Stars"
        />
        GitLab Duo Code Suggestions now available
        <a
          style="color: white; padding-left: 12px; text-decoration: underline"
          href="https://about.gitlab.com/solutions/code-suggestions/"
          >Learn more</a
        >
        <v-icon color="white" icon="mdi-arrow-right-thin" size="medium"></v-icon>
        <img
          style="height: 25px"
          src="https://about.gitlab.com/_nuxt/image/eecfc0.svg"
          alt="Stars"
        />
      </div>
      <div class="nav_bar">
        <nav class="nav_bar">
          <ul>
            <li>
              <a href="https://about.gitlab.com/"
                ><img
                  style="height: 27px"
                  src="../assets/free-gitlab-2.png"
                  alt="logo_icon"
              /></a>
            </li>
            <li>
              <a href="https://about.gitlab.com/why-gitlab/">Why GitLab</a>
            </li>
            <li>
              <a href="https://about.gitlab.com/platform/">Platform</a>
            </li>
            <li>
              <v-row style="padding-left: 5px">
                <v-menu open-on-hover>
                  <template v-slot:activator="{ props }">
                    <a color="primary" v-bind="props"> Solutions </a>
                  </template>
                  <ul class="nav_bar">
                    <li>
                      <v-card class="option_bar">
                        <v-card-title style="color: rgb(238, 75, 129)"
                          >Our solutions</v-card-title
                        >
                        <a>Gitlab Duo (AI)</a><br />
                        <a>Security & Compliance</a><br />
                        <a>Continuous integration & delivery</a><br />
                        <a>Automated software delivery</a><br />
                        <a>Value Stream Management</a><br />
                        <a>Agile Delivery</a><br />
                        <a>Source Code Management</a><br />
                        <a>GitOps</a><br />
                      </v-card>
                    </li>
                    <li>
                      <v-card class="option_bar">
                        <v-card-title style="color: rgb(238, 75, 129)"
                          >By company size</v-card-title
                        >
                        <a>Enterprise</a><br />
                        <a>Small business</a><br />
                        <a>Startups</a><br />
                        <a>Nonprofits</a><br />
                      </v-card>
                      <v-card class="option_bar">
                        <v-card-title style="color: rgb(238, 75, 129)"
                          >By industry</v-card-title
                        >
                        <a>Financial</a><br />
                        <a>Public sector</a><br />
                        <a>Education</a><br />
                      </v-card>
                    </li>
                  </ul> </v-menu
              ></v-row>
            </li>
            <li>
              <a>Pricing</a>
            </li>
            <li>
              <v-row style="padding-left: 5px">
                <v-menu open-on-hover>
                  <template v-slot:activator="{ props }">
                    <a color="primary" v-bind="props"> Resources </a>
                  </template>
                  <ul class="nav_bar">
                    <li>
                      <v-card class="option_bar">
                        <v-card-title style="color: rgb(238, 75, 129)"
                          >Getting Start</v-card-title
                        >
                        <a>Install</a><br />
                        <a>Quick Start Guides</a><br />
                        <a>Learn</a><br />
                        <a>Product documentation</a><br />
                        <a>Best Pravtive videos</a><br />
                        <a>Integrations</a><br />
                      </v-card>
                    </li>
                    <li>
                      <v-card class="option_bar">
                        <v-card-title style="color: rgb(238, 75, 129)"
                          >Discover</v-card-title
                        >
                        <a>Customer success stories</a><br />
                        <a>Blog</a><br />
                        <a>Remote</a><br />
                        <a>TeamOps</a><br />
                        <a>DevSecOps</a><br /><br /><br />
                      </v-card>
                    </li>
                    <li>
                      <v-card class="option_bar">
                        <v-card-title style="color: rgb(238, 75, 129)"
                          >Connect</v-card-title
                        >
                        <a>Community</a><br />
                        <a>Forum</a><br />
                        <a>Events</a><br />
                        <a>Partners</a><br />
                        <br /><br /><br /><br />
                      </v-card>
                    </li>
                  </ul>
                </v-menu>
              </v-row>
            </li>
            <li>
              <v-row style="padding-left: 5px">
                <v-menu open-on-hover>
                  <template v-slot:activator="{ props }">
                    <a color="primary" v-bind="props"> Company </a>
                  </template>
                  <v-card class="option_bar">
                    <a>About</a><br />
                    <a>Jobs</a><br />
                    <a>Events</a><br />
                    <a>Leadership</a><br />
                    <a>Team</a><br />
                    <a>Handbook</a><br />
                    <a>Investor relations</a><br />
                    <a>Trust Center</a><br />
                    <a>Newsletter</a><br />
                    <a>Press</a><br />
                  </v-card>
                </v-menu>
              </v-row>
            </li>
            <li>
              <v-row style="padding-left: 5px">
                <v-menu open-on-hover>
                  <template v-slot:activator="{ props }">
                    <a color="primary" v-bind="props"> Contact us </a>
                  </template>
                  <v-card class="option_bar">
                    <a>Get help</a><br />
                    <a>Customer Portal</a><br />
                  </v-card>
                </v-menu>
              </v-row>
            </li>
            <li style="padding-left: 220px">
              <v-btn icon="mdi-magnify" variant="text"></v-btn>
            </li>
            <li>
              <v-btn variant="tonal">Get Free Trial</v-btn>
            </li>
            <li><a>Sign in</a></li>
          </ul>
        </nav>
      </div>
      <div class="Line_logos">
        <h2><a>Trusted By:</a></h2>
        <a
          ><img
            style="width: 100px"
            src="http://images.ctfassets.net/xz1dnu24egyd/jBj2VNsmT60j2BE3XSGeb/e66c96817462208a24f72efdaf3a68ad/logo_tmobile_mono.svg"
            alt="Tmobile_logo"
        /></a>
        <a
          ><img
            style="width: 75px"
            src="//images.ctfassets.net/xz1dnu24egyd/12sevPjM5gvLhceJRywIKq/36887bd972b75c0c43652532d7054aea/goldman-sachs.svg"
            alt="GoldMan_logo"
        /></a>
        <a
          ><img
            style="width: 100px"
            src="//images.ctfassets.net/xz1dnu24egyd/4vL1UXPcQZiZgxgiPGUcGa/04689a44185ba7bb90e5d365addd983c/arbus.png"
            alt="airbus_logo"
        /></a>
        <a
          ><img
            style="width: 130px"
            src="//images.ctfassets.net/xz1dnu24egyd/12ToPh9IhYXT8DtFZeeWFB/6a5bc582529622f181e69ead7b34c9e6/lockheed-martin.png"
            alt="lock_logo"
        /></a>
        <a
          ><img
            style="width: 100px"
            src="//images.ctfassets.net/xz1dnu24egyd/1MDlrMOt06i5zQ0oRCYAWh/46b70f0979a4898e76ea0cae7e188dce/carfax-logo.png"
            alt="carfa_logo"
        /></a>
        <a
          ><img
            style="width: 100px"
            src="//images.ctfassets.net/xz1dnu24egyd/SC2F82vImYN0O7aITjA22/661c231be70e7dce8b17274ab9068f99/logo_nvidia_mono.svg"
            alt="nvidia_logo"
        /></a>
        <a
          ><img
            style="width: 100px"
            src="//images.ctfassets.net/xz1dnu24egyd/2n7QcbQlYLwERy3ItMgsrP/f5ab9507d15c11d97e3283d757702da8/ubs.svg"
            alt="ubs_logo"
        /></a>
      </div>

      <div class="dashboard01">
        <div>
          <h3
            style="
              font-size: 40px;
              font-weight: 600;
              letter-spacing: -1px;
              line-height: 48px;
            "
          >
            Balance speed and security <br />
            in a single platform
          </h3>
          <br />
          <p style="font-size: 20px; font-weight: 400; line-height: 24px">
            Automate software delivery, boost productivity, and<br />secure your
            end-to-end software supply chain.
          </p>
          <br />
          <v-btn variant="tonal">Discover the platform</v-btn>
          <a>What is GitLab?</a>
        </div>
        <div>
          <img
            src="//images.ctfassets.net/xz1dnu24egyd/5T4fBtZPK48WS8IMUrCJaa/6fd47f98c454bfdf3cc1ddadf769ee17/developer-productivity-img.svg"
            alt=""
          />
        </div>
      </div>

      <div style="margin-top: 64px; margin-bottom: 100px">
        <div class="dashboard02">
          <div>
            <VImg style="width: 35px" :src="svg" />
            <h5>Simplify your toolchain</h5>
            <p>All the <a>essential DevSecOps</a><br />in one place.</p>
          </div>
          <div>
            <VImg style="width: 35px" :src="iconloop" />
            <h5>Accelerate software<br />delivery</h5>
            <p>
              Automation,<a>AI-powered<br />workflows</a>,and more.
            </p>
          </div>
          <div>
            <VImg style="width: 35px" :src="iconsegurity" />
            <h5>Integrate security</h5>
            <p>
              Security that’s <a>built in, notbolted<br />on</a>.
            </p>
          </div>
          <div>
            <VImg style="width: 35px" :src="iconcloud" />
            <h5>Deploy anywhere</h5>
            <p>
              Say goodbye to cloud <a>vendor<br />lock-in</a>.
            </p>
          </div>
        </div>
      </div>

      <div>
        <div class="dashboard03">
          <v-card variant="tonal">
            <v-card-item>
              <div>
                <VImg style="width: 35px" :src="iconclock" />
                <h5>
                  See how <a style="color: palevioletred">Lockheed Martin</a> saves time,
                  money,<br />and tech muscle with GitLab
                </h5>
              </div>
              <div>
                <div class="conteudoDashboard03">
                  <v-chip>
                    <h5>80X</h5>
                    <p>faster CI pipeline builds</p>
                  </v-chip>
                </div>
                <div class="conteudoDashboard03">
                  <v-chip>
                    <h5>90%</h5>
                    <p>less time spent on system maintenance</p>
                  </v-chip>
                </div>
              </div>
              <div style="margin-top: 40px">
                <a>Read story</a>
                <v-icon color="black" icon="mdi-menu-right" size="x-large"></v-icon>
              </div>
            </v-card-item>
          </v-card>
          <div style="display: grid">
            <v-card variant="tonal" max-height="150">
              <v-card-item>
                <div>
                  <VImg style="width: 30px" :src="icontimemoney" />
                  <h5>How much is your toolchain costing you?</h5>
                </div>
                <div style="margin-top: 40px">
                  <a>Try our ROI calculator</a>
                  <v-icon color="black" icon="mdi-menu-right" size="x-large"></v-icon>
                </div>
              </v-card-item>
            </v-card>
            <v-card variant="tonal" max-height="150">
              <v-card-item>
                <div>
                  <VImg style="width: 20px" :src="iconpapel" />
                  <h5>New to GitLab and not sure where to start?</h5>
                </div>
                <div style="margin-top: 40px">
                  <a>Explore resources</a>
                  <v-icon color="black" icon="mdi-menu-right" size="x-large"></v-icon>
                </div>
              </v-card-item>
            </v-card>
          </div>
        </div>
      </div>

      <div class="dashboard04">
        <div style="margin-left: 110px">
          <h2>DevSecOps</h2>
          <br />
          <p>
            From planning to production,<br />
            GitLab brings your team together
          </p>
        </div>

        <div class="dashboard04tabs">
          <v-tabs slider-color="#171321" v-model="tab" bg-color="#171321">
            <v-tab :ripple="false" variant="plain" color="#7759c2" value="one"
              ><v-chip>Development</v-chip></v-tab
            >
            <v-tab :ripple="false" variant="plain" color="#7759c2" value="two"
              ><v-chip>Segurity</v-chip></v-tab
            >
            <v-tab :ripple="false" variant="plain" color="#7759c2" value="three"
              ><v-chip>Operations</v-chip></v-tab
            >
          </v-tabs>
        </div>
        <div>
          <v-window v-model="tab">
            <v-window-item value="one">
              <div class="conteudodashboard04">
                <div>
                  <p>
                    Automated tasks improve efficiency and free up<br />developers’ time —
                    without sacrificing security.
                  </p>
                  <br />
                  <a>Continuous integration and delivery</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                  <a>AI‑powered workflows with GitLab Duo</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                  <a>Source code management</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                  <a>Automated software delivery</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                </div>
                <div>
                  <img
                    style="width: 400px"
                    src="../assets/conteudodashboard04.PNG"
                    alt=""
                  />
                </div>
              </div>
            </v-window-item>

            <v-window-item value="two">
              <div class="conteudodashboard04">
                <div>
                  <p>
                    Manage threat vectors and ensure adherence to<br />compliance
                    standards, without compromising speed.
                  </p>
                  <a>Security and compliance </a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                  <a>Software supply chain security</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                  <a>Integrated testing and remediation</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                  <a>Vulnerability and dependency management</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                </div>
                <div>
                  <img
                    src="//images.ctfassets.net/xz1dnu24egyd/7CQ0hSlvDwRqjFcOVkyURS/17ed8f692247439b735210df0e15ef15/security.svg"
                    alt=""
                  />
                </div>
              </div>
            </v-window-item>

            <v-window-item value="three">
              <div class="conteudodashboard04">
                <div>
                  <p>
                    Automate software deployment and optimize<br />processes, whatever
                    your environment: cloud native,<br />multi-cloud, or legacy.
                  </p>
                  <br />
                  <a>GitOps and infrastructure as code</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                  <a>Automated software delivery</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                  <a>Value stream management</a>
                  <v-icon
                    color="white"
                    icon="mdi-arrow-right-thin"
                    size="medium"
                  ></v-icon>
                  <br /><br />
                </div>
                <div>
                  <img
                    src="//images.ctfassets.net/xz1dnu24egyd/7m2OCfXXtU1EMtjghNlcMy/9e5978ee97220c4e8bd797bc9f615d45/operations.svg"
                    alt=""
                  />
                </div>
              </div>
            </v-window-item>
          </v-window>
        </div>
      </div>

      <div style="margin-top: 140px">
        <div class="dashboard05">
          <div>
            <h1>GitLab is the leading<br />DevSecOps platform</h1>
          </div>
          <div>
            <h3>50%+</h3>
            <p>Fortune 100</p>
          </div>
          <div>
            <h3>30m+</h3>
            <p>Registered users</p>
          </div>
        </div>
      </div>

      <div style="margin-top: 80px">
        <div class="dashboard06">
          <div>
            <v-card variant="tonal">
              <div style="margin: 25px">
                <img
                  style="width: 150px; margin-left: 20px"
                  src="//images.ctfassets.net/xz1dnu24egyd/1mD8hJ4xwe1JllVZ3CXrNs/0151ab72b7b46e511b56ef84919d493c/gartner.svg"
                  alt=""
                />
                <p>
                  GitLab is a Leader in the 2023 Gartner®<br />Magic Quadrant™ for DevOps
                  Platforms
                </p>
                <br />
                <a>Read the report</a>
                <v-icon color="black" icon="mdi-menu-right" size="x-large"></v-icon>
              </div>
            </v-card>
            <br />
            <v-card variant="tonal">
              <div style="margin: 25px">
                <img
                  style="width: 150px; margin-left: 20px"
                  src="//images.ctfassets.net/xz1dnu24egyd/rdWpo3pKJBUFLzDFmTNIE/d69e61550635ebba0556216c44d401a7/forrester-logo.svg"
                  alt=""
                />
                <p>
                  GitLab is the only Leader in The Forrester<br />Wave™: Integrated
                  Software Delivery<br />Platforms, Q2 2023
                </p>
                <br />
                <a>Read the report</a>
                <v-icon color="black" icon="mdi-menu-right" size="x-large"></v-icon>
              </div>
            </v-card>
          </div>
          <div>
            <v-card variant="tonal">
              <div style="margin: 20px">
                <h1>GitLab ranks as a G2 Leader across<br />DevSecOps categories</h1>
                <img
                  style="width: 100px; margin: 25px"
                  src="//images.ctfassets.net/xz1dnu24egyd/712lPKncEMDkCErGOD91KQ/5c1ee2a9fc47e4a2792295168e6f8097/medal__3_.png"
                  alt=""
                />
                <img
                  style="width: 100px; margin: 25px"
                  src="//images.ctfassets.net/xz1dnu24egyd/17EE9DHTQpLyGbJAQslSEk/fcaf9c3a0beca527368425f68d4d4e5a/medal__8_.png"
                  alt=""
                />
                <img
                  style="width: 100px; margin: 25px"
                  src="//images.ctfassets.net/xz1dnu24egyd/1SNrMzYNTrOvEnOuNucAMD/09ae42c6c9c195790916b560298d2454/CloudInfrastructureAutomation_MomentumLeader_Leader.png"
                  alt=""
                />
                <img
                  style="width: 100px; margin: 25px"
                  src="//images.ctfassets.net/xz1dnu24egyd/3UhXS8fSwKieddbliKZEGn/fdd48f41fe1f7280963a2d5b32ea9707/medal__7_.png"
                  alt=""
                />
                <br />
                <img
                  style="width: 100px; margin: 25px"
                  src="//images.ctfassets.net/xz1dnu24egyd/7AODDnwkskODEsylwXkBys/31bcc455720d152fd86e58ecf0b836f6/StaticApplicationSecurityTesting_SAST__Leader_AsiaPacific_Leader.png"
                  alt=""
                />
                <img
                  style="width: 100px; margin: 25px"
                  src="//images.ctfassets.net/xz1dnu24egyd/7jG9DylTxCnElENurGpocF/e087bbbdae5e6e0f7943297ca12433bf/CloudInfrastructureAutomation_Leader_Americas_Leader.png"
                  alt=""
                />
                <img
                  style="width: 100px; margin: 25px"
                  src="//images.ctfassets.net/xz1dnu24egyd/I7XhKHEf8rB7o1zYwYyBf/f58b0d2b51b9a277638d8d0aaf0ce5e7/ValueStreamManagement_Leader_Leader.png"
                  alt=""
                />
                <img
                  style="width: 100px; margin: 25px"
                  src="//images.ctfassets.net/xz1dnu24egyd/712lPKncEMDkCErGOD91KQ/5c1ee2a9fc47e4a2792295168e6f8097/medal__3_.png"
                  alt=""
                />
                <br />
                <a>What industry analysts are saying about GitLab</a>
                <v-icon color="black" icon="mdi-menu-right" size="x-large"></v-icon>
              </div>
            </v-card>
          </div>
        </div>
      </div>

      <div style="margin-top: 130px">
        <div style="margin: 100px">
          <v-card style="background-color: #171321" variant="outlined">
            <div style="margin: 40px">
              <div class="dashboard07">
                <div>
                  <h1>Ready to get started?</h1>
                  <h3>
                    See what your team could do with a unified<br />DevSecOps Platform.
                  </h3>
                  <v-btn>Start free trial</v-btn>
                </div>
                <div>
                  <VImg style="width: 30px" :src="iconpapers" />
                  <p>Find out which plan works best<br />for your team</p>
                  <a>Learn about pricing</a>
                  <v-icon color="white" icon="mdi-menu-right" size="x-large"></v-icon>
                </div>
                <div>
                  <VImg style="width: 30px" :src="iconheadset" />
                  <p>Learn more about what GitLab<br />can do for your team</p>
                  <a>Talk to an expert</a>
                  <v-icon color="white" icon="mdi-menu-right" size="x-large"></v-icon>
                </div>
              </div>
            </div>
          </v-card>
        </div>
      </div>

      <div style="background-color: #171321">
        <div class="dashboard08">
          <div>
            <img
              style="height: 40px; margin: 5px"
              src="../assets/free-gitlab-2.png"
              alt=""
            />
          </div>
          <div>
            <h1>GitLab®</h1>
          </div>
          <div>
            <h3>Platform</h3>
            <a>DevSecOps platform</a>
            <h3>pricing</h3>
            <a>View plans</a><br />
            <a>Why Premium?</a><br />
            <a>Why Ultimate?</a>
          </div>
          <div>
            <h3>Solutions</h3>
            <a>Digital transformation</a><br />
            <a>Security & Compliance</a><br />
            <a>Automated software delivery</a><br />
            <a>Agile Delivery</a><br />
            <a>Cloud transformation</a><br />
          </div>
          <div>
            <h3>Resources</h3>
            <a>Install</a><br />
            <a>Quick start guides</a><br />
            <a>Learn</a><br />
            <a>Product documentation</a><br />
            <a>Blog</a><br />
          </div>
          <div>
            <h3>Company</h3>
            <a>About</a><br />
            <a>Jobs</a><br />
            <a>Leadership</a><br />
            <a>Team</a><br />
            <a>Handbook</a><br />
          </div>
          <div>
            <h3>Contact us</h3>
            <a>Contact an expert</a><br />
            <a>Get help</a><br />
            <a>Customer portal</a><br />
            <a>Status</a><br />
            <a>Terms of use</a><br />
          </div>
        </div>
      </div>
      <div class="dashboard09">
        <div class="conteudodashboard09">
          <p>Language</p>
          <v-select
            bg-color="white"
            label="Select"
            density="compact"
            :items="['English', 'Français']"
          ></v-select>
        </div>
        <div style="padding-right: 20px">
          <v-icon color="white" icon="mdi-youtube" size="x-large"></v-icon>
          <v-icon color="white" icon="mdi-facebook" size="large"></v-icon>
          <v-icon color="white" icon="mdi-linkedin" size="large"></v-icon>
          <v-icon color="white" icon="mdi-twitter" size="large"></v-icon>
        </div>
      </div>
      <v-divider :thickness="3" class="border-opacity-50" color="white"></v-divider>
      <div class="endpage">
        <p>
          Git is a trademark of Software Freedom Conservancy and our use of 'GitLab' is
          under license
        </p>
        <a>View page source</a>
        <a>Please contribute</a>
        <p>© 2024 GitLab B.V.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tab: null,
      tab2: null,
    };
  },
};
</script>

<style>
.banner {
  margin: 0;
  text-align: center;
  background-color: #171321;
  color: white;
  padding: 12px;
  font: message-box;
  font-family: sans-serif;
}
.banner a:hover {
  padding-right: 3px;
}
.nav_bar {
  margin: 0;
  background-color: white;
  text-align: justify;
  align-items: stretch;
}
.nav_bar ul {
  display: flex;
  align-items: center;
  padding-left: 20px;
}
.nav_bar li {
  align-items: stretch;
  display: inline-block;
}
.nav_bar a {
  display: inline-block;
  text-decoration: none;
  align-items: center;
  padding: 15px;
  color: #74717a;
  font-size: 20px;
}
.nav_bar a:hover {
  color: black;
}
.option_bar a {
  display: inline-block;
  text-decoration: none;
  align-items: center;
  padding: 10px;
  color: #74717a;
  font-size: 20px;
}
.option_bar a:hover {
  color: violet;
}
.Line_logos {
  display: flex;
  align-items: center;
  padding-left: 30px;
  margin: 40px;
}
.Line_logos a {
  padding-left: 35px;
  color: #74717a;
  font-size: 20px;
}
.dashboard01 {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
.dashboard01 a {
  padding-left: 40px;
}
.dashboard01 a:hover {
  color: black;
}
.dashboard02 {
  display: flex;
  align-items: stretch;
  justify-content: space-evenly;
}
.dashboard02 h5 {
  font-size: 20px;
  font-weight: 600;
  line-height: 24px;
  font-weight: bold;
}
.dashboard02 p {
  font-size: 16px;
  font-weight: 400;
  line-height: 20px;
}
.dashboard02 a {
  color: #d87093;
}
.dashboard02 a:hover {
  text-decoration: underline;
}
.dashboard03 {
  display: flex;
  align-items: stretch;
  justify-content: space-evenly;
  margin: 70px;
}
.dashboard03 h5 {
  font-size: 24px;
  font-weight: 600;
  letter-spacing: -0.6px;
  line-height: 32px;
}
.dashboard03 p {
  font-size: 14px;
  font-weight: 600;
  line-height: 20px;
  padding-left: 8px;
}
.dashboard03 a {
  font-size: 24px;
  font-weight: 600;
  letter-spacing: -0.6px;
  line-height: 32px;
  color: black;
}
.dashboard03 a:hover {
  transition-delay: 0.2s;
  transition-duration: 0.3s;
  text-decoration: underline;
  padding-right: 8px;
}
.conteudoDashboard03 {
  align-items: center;
  background: #fff;
  border-radius: 90px;
  display: flex;
  margin-top: 16px;
  padding: 8px 24px;
}
.dashboard04 {
  padding: 96px 0 64px;
  background-color: #171321;
}
.dashboard04 h2 {
  font-size: 32px;
  font-weight: 600;
  letter-spacing: -0.8px;
  line-height: 40px;
  color: palevioletred;
}
.dashboard04 p {
  font-size: 50px;
  font-weight: 600;
  letter-spacing: -1.4px;
  line-height: 60px;
  color: white;
}
.dashboard04tabs {
  display: flex;
  margin: 90px;
  justify-content: flex-start;
}
.conteudodashboard04 {
  background-color: #171321;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
.conteudodashboard04 p {
  font-size: 24px;
  font-weight: 400;
  letter-spacing: -0.8px;
  line-height: 32px;
  margin-bottom: 48px;
}
.conteudodashboard04 a {
  font-family: Inter, "sans-serif";
  font-size: 18px;
  font-weight: 600;
  line-height: 20px;
  min-width: 68px;
  color: white;
  padding-bottom: 20px;
}
.dashboard05 {
  display: flex;
  align-items: center;
  justify-content: space-around;
}
.dashboard05 h1 {
  font-size: 50px;
  font-weight: 600;
  letter-spacing: -1.4px;
  line-height: 60px;
}
.dashboard05 h3 {
  font-size: 64px;
  font-weight: 600;
  letter-spacing: -2.1px;
  line-height: 72px;
}
.dashboard05 p {
  font-size: 20px;
  font-weight: 400;
  line-height: 24px;
}
.dashboard06 {
  display: flex;
  align-items: flex-start;
  justify-content: space-evenly;
}
.dashboard06 p {
  padding-top: 25px;
  font-size: 20px;
  font-weight: 400;
  line-height: 24px;
  padding-left: 20px;
  padding-bottom: 10px;
}
.dashboard06 a {
  font-size: 18px;
  font-weight: 600;
  line-height: 20px;
  min-width: 68px;
  padding-top: 20px;
  padding-left: 20px;
}
.dashboard06 a:hover {
  transition-delay: 0.2s;
  transition-duration: 0.3s;
  text-decoration: underline;
  padding-right: 8px;
}
.dashboard07 {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
.dashboard07 h1 {
  font-size: 40px;
  font-weight: 600;
  letter-spacing: -1px;
  line-height: 48px;
  color: palevioletred;
  padding-bottom: 15px;
}
.dashboard07 h3 {
  font-size: 24px;
  font-weight: 400;
  letter-spacing: -0.8px;
  line-height: 32px;
  color: white;
  padding-bottom: 20px;
}
.dashboard07 p {
  font-size: 16px;
  font-weight: 400;
  line-height: 20px;
  color: white;
  padding-bottom: 15px;
  margin-top: 25px;
}
.dashboard07 a {
  font-size: 18px;
  font-weight: 600;
  line-height: 20px;
  color: white;
}
.dashboard07 a:hover {
  transition-delay: 0.2s;
  transition-duration: 0.3s;
  text-decoration: underline;
  padding-right: 8px;
}
.dashboard08 {
  display: flex;
  align-items: stretch;
  justify-content: space-evenly;
  background-color: #171321;
  padding-top: 30px;
}
.dashboard08 h1 {
  color: white;
}
.dashboard08 h3 {
  padding-left: 25px;
  padding-bottom: 10px;
  padding-top: 10px;
  color: white;
}
.dashboard08 a {
  padding-left: 25px;
  color: white;
}
.dashboard08 a:hover {
  text-decoration: underline;
}
.dashboard09 {
  background-color: #171321;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.conteudodashboard09 {
  display: flex;
  width: 250px;
  background-color: #171321;
  padding-top: 50px;
  padding-left: 20px;
}
.conteudodashboard09 p {
  color: white;
  padding-right: 10px;
}
.endpage {
  background-color: #171321;
  padding: 20px;
}
.endpage p {
  color: white;
}
.endpage a {
  color: white;
  padding-right: 8px;
  text-decoration: underline;
}
</style>
