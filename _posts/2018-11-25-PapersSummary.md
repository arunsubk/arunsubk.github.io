---
layout: posts
title: "Summary of papers read by me, in Face recognition"
date: 2018-11-25
---

<html>
  <body>
    <p><b>Paper: </b><a href="https://arxiv.org/abs/1603.07057/">Do-we-really-need-millions-of-images</a>
      <b>Summary: </b>This paper talks about using data augmentation as a means to avoid a lot of data. Uses CNN of augemnted data. Tests finally of LFW (though clearly doesn't aim at beating the highest accuracies due to unavailablity of commercial achievers' resource details). But asserts it clearly provides an alternative to creating/search-for a lot of labelled data.
        </p>
    <br>
    <br>
    <p><b>Paper: </b><a href="https://arxiv.org/abs/1811.08565">Priming Deep neural netowrks with Synthetic faces</a>
    </p>
    <b>Summary: </b>Techniques to Prime the neural network with creating synthetic using a 3d generator are used. The resulting synthetic labelled data is used along with limited training data to show big improvements on all standard datasets. Further this is shown to be better than data augmentation. Software to generate such is made open source.
    <br>
    <br>
    <p><b>Paper: </b><a href="https://arxiv.org/abs/1811.08345"> LGLG-WPCA: An Effective Texture-based Method for Face Recognition</a></p>
      <b>Summary: </b>Using Learning Gabor Log-Euclidean Gaussian, called LGLG-WPCA for feature extraction of face images in 'adverse conditions' such as uneven illumination, varying poses and skin aging. As per author, since the space of Gaussian is a Reimannian manifold, he is employing LGLG to map in a linear space and further using Whitening PCA for feature reduction.
    <br>
    <br>
    <p><b>Paper: </b><a href="https://arxiv.org/pdf/1811.07753.pdf">Contextual face-recognition with a nested-hierarchial non-parametric model</a></p>
    <b>Summary: </b> Leveraging the 'context' of the subject's presence to aid face recognition. No experimental proof. But the model of features and labels is given.
    
  </body>
</html>
      
  
