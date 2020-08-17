---


---

<h1 id="project-part-of-speech-tagging">Project: Part of Speech Tagging</h1>
<h2 id="introduction">Introduction</h2>
<p>In this notebook, you’ll use the  <a href="https://github.com/jmschrei/pomegranate">Pomegranate</a>  library to build a hidden Markov model for part of speech tagging with a  <a href="http://www.petrovi.de/data/universal.pdf">universal tagset</a>. Hidden Markov models have been able to achieve &gt;96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.</p>
<p>The notebook already contains some code to get you started. You only need to add some new functionality in the areas indicated to complete the project; you will not need to modify the included code beyond what is requested. Sections that begin with  <strong>‘IMPLEMENTATION’</strong>  in the header indicate that you must provide code in the block that follows. Instructions will be provided for each section, and the specifics of the implementation are marked in the code block with a  <code>'TODO'</code>  statement. Please be sure to read the instructions carefully!</p>
<p><strong>NOTE:</strong>  There is an optional warmup exercise to introduce the Pomegranate API included in the project files. Just launch the  <code>HMM warmup (optional).ipynb</code>  file first to get started there, then complete the  <code>hmm tagger.ipynb</code>  notebook. (Only the tagger will be submitted for review.)</p>
<h2 id="getting-started">Getting Started</h2>
<p>You can choose one of two ways to complete the project. The first method is to use the Workspace embedded in the classroom in the next lesson. The Workspace has already been configured with all the required project files for you to complete the project. Simply open the lesson, complete the sections indicated in the Jupyter notebook, and then click the “submit project” button.</p>
<p><strong>NOTE:</strong>  If you are prompted to select a kernel when you launch a notebook, choose the  <strong>Python 3</strong>  kernel.</p>
<p>Alternatively, you can download a copy of the project materials and then run a Jupyter server locally on your machine. Select the appropriate link for your program below, then follow the instructions in the readme to setup and complete the project.</p>
<p><strong>NOTE:</strong>  These steps are  <strong>not</strong>  required if you are using the project Workspace.</p>
<ul>
<li>AIND GitHub:  <a href="https://github.com/udacity/artificial-intelligence">here</a>  (Projects/4_HMM Tagger)</li>
<li>NLPND GitHub:  <a href="https://github.com/udacity/hmm-tagger">here</a></li>
</ul>
<h2 id="evaluation">Evaluation</h2>
<p>Your project will be reviewed by a Udacity reviewer against the project rubric  <a href="https://review.udacity.com/#!/rubrics/1429/view">here</a>. Review this rubric thoroughly, and self-evaluate your project before submission. All criteria found in the rubric must meet specifications for you to pass.</p>
<h2 id="submission">Submission</h2>
<p>Once you have completed all of the code implementations, you need to finalize your work by exporting the iPython Notebook as an HTML document. Before exporting the notebook to html, all of the code cells need to have been run so that reviewers can see the final implementation and output. You must then export the notebook by running the last cell in the notebook, or by using the menu above and navigating to File -&gt; Download as -&gt; HTML (.html) Your submissions should include both the html and ipynb files.</p>
<p>Add the “hmm tagger.ipynb” and “hmm tagger.html” files to a zip archive and submit it with the button below. (<strong>NOTE:</strong>  If you complete the project in the workspace, then you can submit directly using the “submit” button in the workspace.)</p>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

