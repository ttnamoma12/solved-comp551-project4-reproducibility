Download Link: https://assignmentchef.com/product/solved-comp551-project4-reproducibility
<br>
Reproducibility (i.e., the ability for researchers to replicate others’ work) is a critical issue in machine learning, and there is a growing movement towards ensuring reproducible machine learning. In this mini-project, you will aim to reproduce the results of a published machine learning paper. There are two different tracks: the first track aims to reproduce and extend on results from papers that did not publish code, and the second track aims to use published code to reproduce and extend on an existing work. You must either:

<ol>

 <li>Choose a paper from the following curated list: gl/aVLcaY.</li>

 <li>Already be registered to participate in the NeurIPS Reproducibility Challenge—in which case you willreproduce the paper you registered for.</li>

 <li>Receive special permission from the instructor to reproduce a different paper. If you choose a paperyourself, it should be published in well-known peer-reviewed machine learning venue (e.g., ICML, AAAI, NeurIPS, ACL, CVPR, or ICLR) and have been published no earlier than 2015.</li>

</ol>

<strong>Disclaimer 1: Not all papers are easily reproducibile. Failing to reproduce the exact results of the original paper is not necessarily a bad thing, as long as your experiments are rigorous!</strong>

<strong>Disclaimer 2: Fully reproducing some papers or baselines will require more computational resources than you have access to. You should keep this in mind when you choose a paper, but it is also okay to only work on a subset of the data/tasks in a paper, in order to make things tractable.</strong>

<h2>Track 1: Implement and improve the baselines</h2>

When researchers propose new models, they often spend more time on fine-tuning their proposed model than fine-tuning the baselines. Simple baselines like Naive Bayes, Random Forests, k-NN if properly tuned, can sometimes provide performances that are hard to beat. In this track, your goal will be to select a paper (e.g., from the list of suggested papers) and improve/analyze the baselines for the tasks considered in the paper. First implement (a subset of) the baseline(s) mentioned in the paper (without using the author’s code) and try to reproduce the baseline performance reported in the paper. Then try to fine-tune the baselines by doing extensive hyper-parameter tuning. Then, explore simple machine learning algorithms (e.g., discussed in the class) to improve the performance on the given task. Note that for some recent papers a simple/standard LSTM or CNN would count as a baseline. Your job is to act like an adversary to the paper and try to beat their performance by using simple algorithms that have less computational complexity. <strong>At a minimum, in this track you should reproduce at least one baseline proposed in the paper and implement one modified baseline of your own. An outstanding project in this track would perform a rigorous and extensive evaluation many simple baselines and/or propose a clever new baseline that achieves strong performance.</strong>

<h2>Track 2: Reproduce and modify the model</h2>

The goal of this track is to take a published machine learning model (e.g., from the given list of papers) <strong>that comes with published code </strong>and try to explore the proposed model in depth. Specifically, you will first reproduce the results reported in the paper by running the code provided by the authors. Then you will try to modify the model and perform ablation studies to understand the model’s robustness and evaluate the importance of the various model components. (In this context, the term “ablation” is used to describe the process of removing different model components to see how it impacts performance.) You can also try to improve the model based on your experiments. You should do a thorough analysis of the model through an extensive set of experiments. Note that some experiments will be difficult to replicate due to computational resources. It is fine to reproduce only a subset of the original paper’s results or to work on a smaller variant of the data—if necessary. <strong>At a minimum, in this track you should use the authors code to reproduce a non-trivial subset of their results and explore how the model performs after you make minor modifications (e.g., changes to hyperparameters). An outstanding project in this track would perform very a detailed ablation study and/or implement significant/meaningful extensions of the model.</strong>

<h1>Deliverables</h1>

You must submit two separate files to MyCourses (<strong>using the exact filenames and file types outlined below</strong>):

<ol>

 <li><strong>zip</strong>: A collection of supporting code files. Please submit a README detailing the packages you used and providing instructions to replicate your results.</li>

 <li><strong>pdf</strong>: Your project write-up as a pdf (details below).</li>

</ol>

In addition, you must form a team and choose a paper by November 27th at 11:59pm. One member of your team must fill in the following form by that date: https://forms.gle/vPiqmT27qM2U5SME7.

<h2>Project write-up</h2>

Your team must submit a project write-up that is a maximum of eight pages (single-spaced, 10pt font or larger; extra pages for references/bibliographical content and appendices can be used). We highly recommend that students use LaTeX to complete their write-ups and use the bibtex feature for citations. <strong>You are free to structure the report how you see fit, but you should clearly summarize/describe the paper/task you are reproducing, reference relevant related works, describe the baselines/modifications you implemented, and clearly present your results.</strong>

You must include a statement of contributions at the end of your report, which specifies what each group member contributed.

<h2>Clarifications for the NeurIPS Reproducibility Challenge</h2>

To be eligible for the bonus 10 points, you must:

<ul>

 <li>Already be registered for the NeurIPS Reproduciblity Challenge.</li>

 <li>Submit a project report to MyCourses by the class deadline on December 14th.</li>

 <li>Also submit a report to the challenge website by December 27th. This can be the same report you submitted to the class, or you can improve this report based on the feedback you receive.</li>

</ul>

<h1>Evaluation</h1>

The mini-project is out of 100 points. <strong>Teams that participate in the NeurIPS Reproducibility Challenge will be graded out of 110 points, with the extra 10 points being a potential bonus. </strong>Your grade will be based on your submitted write-up, as well as the supporting code. As with the previous mini-projects your write-up will be judged according its scientific quality (included but not limited to):

<ul>

 <li>Is your proposed methodology technically sound? For example, in Track 1, are your baselines appropriate for the task and properly implemented? For Track 2, are the modifications you made reasonable and properly implemented?</li>

 <li>How detailed/rigorous/extensive are your experiments?</li>

 <li>Does your report clearly describe the task you are working on (i.e., the paper you are reproducing), the experimental set-up, results, figures (e.g., don’t forget axis labels and captions on figures, don’t forget to explain figures in the text).</li>

 <li>Is your report well-organized and coherent?</li>

 <li>Is your report clear and free of grammatical errors and typos?</li>

 <li>Does your report include an adequate discussion of related work and citations?</li>

</ul>