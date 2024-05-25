  <h3>Multimodal-Question-Answering-Model</h3>
  <hr>
  <h6>
  <ul>
    <li>BERT and ViT are indeed multimodal models that have been utilized in various applications, particularly in the field of multimodal deep learning.</li>
    <li> BERT, which stands for Bidirectional Encoder Representations from Transformers, is an encoder-only Transformer model that excels in natural language processing tasks 
         by predicting masked tokens based on context. On the other hand, ViT, or Vision Transformer, revolutionized computer vision tasks by treating images as fixed-size 
         patches and creating embeddings from them. ViT uses a standard Transformer encoder to process images, allowing for efficient handling of visual data without 
         convolutions.</li>
    <li>These multimodal models, by integrating the strengths of BERT and ViT, have significantly advanced the capabilities of machines to understand and interpret data from 
         different modalities, leading to breakthroughs in tasks such as visual question answering</li>
  </ul>
  </h6>
  <hr>
  <h4>Know our Project</h4>
  <h6>
    <ul>
    <li>We have tried 4 different combinations of bert and vit family, with and without using LORA on VQAv2 dataset available from Hugging Face.</li>
    <li>Each folder contains the code of:
      <ul>
        <li>Training the model by giving questions, images, answers and then doing the validation test, to check whether the model giving correct results or not.</li>
        <li>Testing the model by giving question and image and the model predicts the answer.</li>
        <li>Lightning-logs:Contain the graph of the metrices: Accuracy, F1 Score, Precision, Recall and Time Taken for Training (TTT).</li>
        <li>To see the graph of the metrices with Tensorboard, write the following code on Google Collab.</li>
       

      #Showing just one example from our code of lightning_logs of vit-albert-lora model and this file is contained under the folder vit+albert+lora+15000datapts+15epochs/vit-albert-lora- precision
      from google.colab import drive
      drive.mount('/content/drive')
      
      %load_ext tensorboard
      %tensorboard --logdir /content/drive/MyDrive/VR_FinalProject_End_Term/VR_PROJECT_FINAL_PROJECT1/VR_PROJECT/vit+albert+lora+15000datapts+15epochs/vit-albert-lora- precision/lightning_logs



      
<li>We are storing the checkpoints of every model and can be used later.</li>

</ul>
</li>
</ul>
</h6>
<hr>
<h4> To get the detailed analysis of our project, just check the Project Report naming "VR_Final_Report_VQAProject.pdf"</h4>


