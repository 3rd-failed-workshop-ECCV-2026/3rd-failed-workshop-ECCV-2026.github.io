---
title: Keynote Speakers
nav: true
---

## Keynote Speakers

<div style="display:grid; grid-template-columns:repeat(3,minmax(0,1fr)); gap:24px; margin-top:24px; align-items:start;">

  <!-- Elisa Ricci -->
  <div style="padding:22px; border:1px solid #e5e7eb; border-radius:20px; background:#fff; box-shadow:0 6px 18px rgba(0,0,0,0.08); text-align:center;">

    <img
      src="https://eliricci.eu/wp-content/uploads/2023/09/Elisa_Ricci-300x300-1.jpeg"
      alt="Elisa Ricci"
      width="150"
      height="150"
      style="width:150px; height:150px; border-radius:50%; object-fit:cover; box-shadow:0 4px 12px rgba(0,0,0,0.16); margin-bottom:14px;">

    <h3 style="margin:8px 0 6px 0;">
      <a href="https://eliricci.eu/" style="text-decoration:none;">
        Elisa Ricci
      </a>
    </h3>

    <p style="margin:0;">
      <strong>Talk Title:</strong>
      Diagnose, Debias, Forget: Rethinking Fairness Across the Vision-Language Model Lifecycle
    </p>

    <details style="margin-top:14px; padding-top:14px; border-top:1px solid #e5e7eb;">
      <summary style="cursor:pointer; font-weight:600; color:#2563eb;">
        Read abstract
      </summary>

      <p style="margin:14px 0 0; text-align:left; line-height:1.6; color:#374151;">
        Vision-language models inherit and amplify societal biases at every stage of their lifecycle: in the representations they learn, the behaviors they exhibit at inference time, and even in how they respond to requests to forget data. This talk presents three complementary perspectives on tackling bias in CLIP and multimodal LLM systems. First, we look inside the model: SITH performs data-free, training-free interpretability of the vision transformer of CLIP, decomposing attention-head weights via singular value decomposition and mapping them to human-interpretable concepts. This enables targeted interventions to suppress bias and spurious correlations without any data or retraining. Second, we act on what we find: SEM performs post-hoc debiasing of vision-language models in a sparse, disentangled embedding space, modulating bias-related neurons while preserving task-relevant semantics, improving fairness in retrieval and zero-shot classification without retraining. Third, we focus on fair unlearning: when deletion requests are demographically skewed, naive unlearning can introduce new bias. We present FairGet, a VQA benchmark for fairness-aware unlearning built on 4,000 fictitious identities, and FAUN, a method combining activation steering with bias-aware PCA to forget data while preserving demographic parity.

      </p>
    </details>

  </div>


  <!-- Steffen Schneider -->
  <div style="padding:22px; border:1px solid #e5e7eb; border-radius:20px; background:#fff; box-shadow:0 6px 18px rgba(0,0,0,0.08); text-align:center;">

    <img
      src="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=KR5dj44AAAAJ&citpid=9"
      alt="Steffen Schneider"
      width="150"
      height="150"
      style="width:150px; height:150px; border-radius:50%; object-fit:cover; box-shadow:0 4px 12px rgba(0,0,0,0.16); margin-bottom:14px;">

    <h3 style="margin:8px 0 6px 0;">
      <a href="https://stes.io/" style="text-decoration:none;">
        Steffen Schneider
      </a>
    </h3>

    <p style="margin:0;">
      <strong>Talk Title:</strong> TBD
    </p>

    <details style="margin-top:14px; padding-top:14px; border-top:1px solid #e5e7eb;">
      <summary style="cursor:pointer; font-weight:600; color:#2563eb;">
        Read abstract
      </summary>

      <p style="margin:14px 0 0; text-align:left; line-height:1.6; color:#374151;">
        <strong>Abstract:</strong> TBD
      </p>
    </details>

  </div>


  <!-- Andrew King -->
  <div style="padding:22px; border:1px solid #e5e7eb; border-radius:20px; background:#fff; box-shadow:0 6px 18px rgba(0,0,0,0.08); text-align:center;">

    <img
      src="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=mA_tZpMAAAAJ&citpid=8"
      alt="Andrew King"
      width="150"
      height="150"
      style="width:150px; height:150px; border-radius:50%; object-fit:cover; box-shadow:0 4px 12px rgba(0,0,0,0.16); margin-bottom:14px;">

    <h3 style="margin:8px 0 6px 0;">
      <a href="https://www.kcl.ac.uk/people/andrew-king" style="text-decoration:none;">
        Andrew King
      </a>
    </h3>

    <p style="margin:0;">
      <strong>Talk Title:</strong>
      Understanding Bias in AI for Medical Imaging
    </p>

    <details style="margin-top:14px; padding-top:14px; border-top:1px solid #e5e7eb;">
      <summary style="cursor:pointer; font-weight:600; color:#2563eb;">
        Read abstract
      </summary>

      <p style="margin:14px 0 0; text-align:left; line-height:1.6; color:#374151;">
        AI models for medical imaging can exhibit systematic differences in performance across demographic groups, for example by sex or ethnicity. In healthcare, where AI is increasingly being integrated into clinical decision-making, such disparities risk perpetuating or exacerbating existing health inequalities. Although a wide range of generic bias mitigation methods have been proposed, their effectiveness in medical imaging has been mixed. Medical imaging datasets are often relatively small compared with those used in computer vision, and models must contend with complex domain shifts arising from differences in scanners, acquisition protocols, clinical settings, and patient populations. In this talk, I will describe a research programme that takes a different approach: rather than attempting to mitigate bias without first understanding its causes, we seek to identify what the model is learning that leads to disparities and use this understanding to develop targeted mitigation strategies. I will show how this process can now be largely automated, enabling effective identification and mitigation of sources of bias across domain shifts. This targeted approach can substantially outperform generic bias mitigation methods and can even mitigate bias without the commonly observed accuracy-fairness trade-off. The talk will highlight the importance of understanding model behaviour, not simply measuring its outcomes, as a route towards developing more reliable and equitable medical imaging AI.
      </p>
    </details>

  </div>

</div>
