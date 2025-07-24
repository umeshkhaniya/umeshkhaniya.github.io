
### Welcome to my Website

<table>
  <tr>
    <td style="vertical-align: top; padding-right: 20px;">
      <img src="assets/umesh_profile.jpg" alt="Umesh Khaniya" style="width: 180px; border-radius: 50%;">
    </td>
    <td style="vertical-align: top;">
      <h2>Hi, I'm Umesh Khaniya</h2>
      <p>
        I am a postdoctoral researcher at NIH working on antibody engineering, CAR-T cell modeling, and computational immunology.  
        My focus includes structure-based analysis of Ig folds, machine learning–based topology labeling, and predicting domain-domain interactions.
      </p>
    </td>
  </tr>
</table>

---

# Education

- **Ph.D. in Physics**, *CUNY Graduate Center*, 2016–2022  
- **Master in Physics**, *Tribhuvan University, Nepal*, 2013–2015



# 🔬 Key Skills

-	**MD & Docking**: NAMD, GROMACS, OpenMM, CHARMM-GUI, MM-PBSA, FEP, Schrödinger BioLuminate, AutoDock, PIPER
-	**Protein Modeling**: AlphaFold (AF2/AF3), ESMFold, RoseTTAFold, Modeller, Chai Discovery
-	**ML**: Graph Neural Networks, Transformer Models, Diffusion Models, Hugging Face, Fine-Tuning
-	**Frameworks**: PyTorch, TensorFlow, scikit-learn, PySpark
-	**Protein-Ligand Docking**: Schrödinger BioLuminate, PIPER, AutoDock
-	**Cheminformatics**: RDKit, PaDEL
-	**Programming**: Python, SQL, Bash, R
-	**Cloud & DevOps**: AWS (EC2, S3, Redshift, Lambda), HPC environments, Docker, Git, Airflow
-	**Visualization & Tools**: VMD, PyMol, UCSF Chimera, Jupyter Notebook

<!-- Tabs -->
<style>
  .tab {
    overflow: hidden;
    border-bottom: 1px solid #ccc;
  }

  .tab button {
    background-color: inherit;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 12px 18px;
    transition: 0.3s;
    font-size: 16px;
  }

  .tab button:hover {
    background-color: #ddd;
  }

  .tab button.active {
    background-color: #ccc;
  }

  .tabcontent {
    display: none;
    padding: 12px;
    border-top: none;
  }
</style>

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Bio')" id="defaultOpen">Bio</button>
  <button class="tablinks" onclick="openTab(event, 'Papers')">Papers</button>
  <button class="tablinks" onclick="openTab(event, 'Experience')">Experience</button>
  <button class="tablinks" onclick="openTab(event, 'Hobby')">Hobby</button>
  <button class="tablinks" onclick="openTab(event, 'Projects')">Projects</button>
</div>

<!-- Tab Contents -->
<div id="Bio" class="tabcontent">
  <h3>Bio</h3>
  <p>Postdoc at NIH working on antibody engineering, CAR-T cell modeling, and immunoglobulin fold analysis.</p>
</div>

<div id="Papers" class="tabcontent">
  <h3>Publications</h3>
  <ul>
    <li>Khaniya, U. et al. *Title*, Journal, Year.</li>
    <li>Another paper…</li>
  </ul>
</div>

<div id="Experience" class="tabcontent">
  <h3>Experience</h3>
  <p>NIH Postdoctoral Fellow, 2022–Present</p>
  <p>Research Assistant, CUNY, 2016–2022</p>
</div>

<div id="Hobby" class="tabcontent">
  <h3>Hobbies</h3>
  <p>Hiking, playing chess, traveling, photography</p>
</div>

<div id="Projects" class="tabcontent">
  <h3>Projects</h3>
  <ul>
    <li>ML-based topology labeling of Ig folds</li>
    <li>Domain-domain interaction classifier</li>
  </ul>
</div>

<script>
  function openTab(evt, tabName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
      tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
      tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(tabName).style.display = "block";
    evt.currentTarget.className += " active";
  }
  // Auto-open default tab
  document.getElementById("defaultOpen").click();
</script>


#### 📂 Projects
- **IgStrand Universal Numbering**: Structural classification of Ig domains across proteomes using TM-align and AF2 models.
- **CAR-T Modeling**: Developed pipelines to simulate and evaluate synthetic CAR-T constructs using MD simulations and structural prediction tools.

[Download CV](assets/UmeshKhaniya_CV.pdf)
