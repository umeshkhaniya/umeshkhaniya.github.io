
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

<style>
  .tab {
    overflow: hidden;
    border-bottom: 1px solid #ccc;
  }
  .tab button {
    background-color: inherit;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 10px 20px;
    transition: 0.3s;
    font-size: 17px;
  }
  .tab button:hover {
    background-color: #ddd;
  }
  .tab button.active {
    background-color: #ccc;
  }
  .tabcontent {
    display: none;
    padding: 20px 0;
  }
</style>

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Bio')" id="defaultOpen">Bio</button>
  <button class="tablinks" onclick="openTab(event, 'Papers')">Papers</button>
  <button class="tablinks" onclick="openTab(event, 'Experience')">Experience</button>
  <button class="tablinks" onclick="openTab(event, 'Hobby')">Hobby</button>
  <button class="tablinks" onclick="openTab(event, 'Projects')">Projects</button>
</div>

<div id="Bio" class="tabcontent">
  <h2>Bio</h2>
  <p>I am a postdoctoral researcher at NIH focused on antibody engineering, CAR-T modeling, and machine learning-based structural analysis.</p>
</div>

<div id="Papers" class="tabcontent">
  <h2>Papers</h2>
  <ul>
    <li>Paper 1: Title and link</li>
    <li>Paper 2: Title and link</li>
  </ul>
</div>

<div id="Experience" class="tabcontent">
  <h2>Experience</h2>
  <ul>
    <li>Postdoc, NIH (2022–Present)</li>
    <li>Graduate Researcher, CUNY (2016–2022)</li>
  </ul>
</div>

<div id="Hobby" class="tabcontent">
  <h2>Hobby</h2>
  <p>Hiking, photography, and reading about AI and science history.</p>
</div>

<div id="Projects" class="tabcontent">
  <h2>Projects</h2>
  <ul>
    <li>IgStrand universal numbering</li>
    <li>CAR-T structure prediction</li>
  </ul>
</div>

<script>
  function openTab(evt, tabName) {
    var i, tabcontent, tablinks
    tabcontent = document.getElementsByClassName("tabcontent")
    for (i = 0; i < tabcontent.length; i++) {
      tabcontent[i].style.display = "none"
    }
    tablinks = document.getElementsByClassName("tablinks")
    for (i = 0; i < tablinks.length; i++) {
      tablinks[i].className = tablinks[i].className.replace(" active", "")
    }
    document.getElementById(tabName).style.display = "block"
    evt.currentTarget.className += " active"
  }
  document.getElementById("defaultOpen").click()
</script>



#### 📂 Projects
- **IgStrand Universal Numbering**: Structural classification of Ig domains across proteomes using TM-align and AF2 models.
- **CAR-T Modeling**: Developed pipelines to simulate and evaluate synthetic CAR-T constructs using MD simulations and structural prediction tools.

[Download CV](assets/UmeshKhaniya_CV.pdf)
