---
layout: page
title: "Purrfessor"
description: "A Fine-tuned LLaVA Diet Health Chatbot."
img: assets/img/catbot.jpg
importance: 1
category: work
---

<div class="row">
  <!-- 左侧：图片 + 按钮 -->
  <div class="col-md-5 text-center">
    <img src="{{ 'assets/img/catbot.jpg' | relative_url }}" 
         alt="Purrfessor Chatbot" 
         class="img-fluid rounded shadow-sm mb-4" 
         style="max-width: 400px;">

    <div class="mt-2">
      <a href="https://arxiv.org/abs/2411.14925" 
         class="btn btn-sm btn-paper me-2" target="_blank">arXiv</a>
      <a href="{{ '/assets/pdf/2411.14925v1.pdf' | relative_url }}" 
         class="btn btn-sm btn-paper me-2" target="_blank">PDF</a>
      <a href="https://purrfessorbot.netlify.app/" 
         class="btn btn-sm btn-paper" target="_blank">Demo</a>
    </div>
  </div>

  <!-- 右侧：简短 summary -->
  <div class="col-md-7 ">
    <p>
      Purrfessor is a multimodal health chatbot that analyzes meals 
      with images + text and offers personalized diet guidance.  
      Fine-tuned on food and nutrition data, it improves user engagement and care 
      compared to standard GPT-4.
    </p>
  </div>
</div>
