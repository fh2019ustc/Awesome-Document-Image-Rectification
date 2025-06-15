# Awesome Document Image Rectification [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)
> A comprehensive list of awesome document image rectification methods based on deep learning.
## Table of contents

- [Papers](#papers)
- [Datasets](#datasets)
- [Demos](#demos)


# Papers


|***Year***|***Venue***|***Title***|***Repo***|***Result***|
|----|----|-----|----|----|
|2018|CVPR|[DocUNet: Document Image Unwarping via A Stacked U-Net](https://openaccess.thecvf.com/content_cvpr_2018/papers/Ma_DocUNet_Document_Image_CVPR_2018_paper.pdf)|||
|2019|TOG|[Document Rectification and Illumination Correction using a Patch-based CNN*](https://arXiv.org/pdf/1909.09470.pdf)|[Code](https://github.com/xiaoyu258/DocProj)||
|2019|ICCV|[DewarpNet: Single-Image Document Unwarping With Stacked 3D and 2D Regression Networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Das_DewarpNet_Single-Image_Document_Unwarping_With_Stacked_3D_and_2D_Regression_ICCV_2019_paper.pdf)|[Code](https://github.com/cvlab-stonybrook/DewarpNet)|[Link](https://drive.google.com/drive/folders/1aPfQHGrGxpuIbYLONydbSkGNygRX2z2P?usp=sharing)|
|2020|PR|[Geometric Rectification of Document Images using Adversarial Gated Unwarping Network](https://reader.elsevier.com/reader/sd/pii/S0031320320303794?token=52ED03E7C85352F1F088C41DA2BEED447A34798498EBC41ADF333A84742F53C1904FFED32E91578195D63663F9006F3D&originRegion=us-east-1&originCreation=20220801125708)|||
|2020|CVPR|[BEDSR-Net: A Deep Shadow Removal Network From a Single Document Image*](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lin_BEDSR-Net_A_Deep_Shadow_Removal_Network_From_a_Single_Document_CVPR_2020_paper.pdf)|||
|2020|ECCV|[Can You Read Me Now? Content Aware Rectification using Angle Supervision](https://arXiv.org/pdf/2008.02231.pdf)|||
|2020|DAS|[Dewarping Document Image by Displacement Flow Estimation with Fully Convolutional Network](https://arXiv.org/pdf/2104.06815.pdf)|[Code](https://github.com/gwxie/Dewarping-Document-Image-By-Displacement-Flow-Estimation)||
|2020|BMVC|[Intrinsic Decomposition of Document Images In-the-wild*](https://arXiv.org/pdf/2011.14447.pdf)|[Code](https://github.com/cvlab-stonybrook/DocIIW)||
|2021|ACM MM|[DocTr: Document Image Transformer for Geometric Unwarping and Illumination Correction*](https://arXiv.org/pdf/2110.12942.pdf)|[Code](https://github.com/fh2019ustc/DocTr)|[Link](https://drive.google.com/drive/folders/1kJ34Nk18RVPwYK8mdfcQvU_67whD9tMe?usp=sharing)|
|2021|ICCV|[End-to-end Piece-wise Unwarping of Document Images](https://openaccess.thecvf.com/content/ICCV2021/papers/Das_End-to-End_Piece-Wise_Unwarping_of_Document_Images_ICCV_2021_paper.pdf)|[Code](https://github.com/sagniklp/PiecewiseUnwarp)||
|2021|ICDAR|[Document Dewarping with Control Points](https://arXiv.org/pdf/2203.10543.pdf)|[Code](https://github.com/gwxie/Document-Dewarping-with-Control-Points)|
|2022|CVPR|[Fourier Document Restoration for Robust Document Dewarping and Recognition](https://openaccess.thecvf.com/content/CVPR2022/papers/Xue_Fourier_Document_Restoration_for_Robust_Document_Dewarping_and_Recognition_CVPR_2022_paper.pdf)|||
|2022|CVPR|[Revisiting Document Image Dewarping by Grid Regularization](https://openaccess.thecvf.com/content/CVPR2022/papers/Jiang_Revisiting_Document_Image_Dewarping_by_Grid_Regularization_CVPR_2022_paper.pdf)||[Link](https://drive.google.com/drive/folders/1Czgy0s2CbLrs__a-Q838fzre3tWhaTjq?usp=share_link)|
|2022|ACM MM|[Marior: Margin Removal and Iterative Content Rectification for Document Dewarping in the Wild](https://arXiv.org/pdf/2207.11515.pdf)||[Link](https://github.com/ZZZHANG-jx/Marior)|
|2022|ACM MM|[UDoc-GAN: Unpaired Document Illumination Correction with Background Light Prior*](https://dl.acm.org/doi/abs/10.1145/3503161.3547916)|[Code](https://github.com/harrytea/UDoc-GAN)||
|2022|SIGGRAPH|[Learning From Documents in the Wild to Improve Document Unwarping](https://dl.acm.org/doi/pdf/10.1145/3528233.3530756)|[Code](https://github.com/cvlab-stonybrook/PaperEdge)|[Link](https://drive.google.com/file/d/1QM3Y5Ty96ydVCQPNqR0_bnMG9oqIQkGm/view?usp=sharing)|
|2022|ECCV|[Geometric Representation Learning for Document Image Rectification](https://arXiv.org/pdf/2210.08161.pdf)|[Code](https://github.com/fh2019ustc/DocGeoNet)|[Link](https://pan.baidu.com/s/16xnV2Sv7xliUO_5bVGDo-Q?pwd=nszy)|
|2022|ECCV|[Learning an Isometric Surface Parameterization for Texture Unwrapping](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136970568.pdf)|[Code](https://github.com/cvlab-stonybrook/Iso-UVField)||
|2022|ICPR|[Document Image Rectification in Complex Scene Using Stacked Siamese Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9956331&casa_token=3EP6PWPjea0AAAAA:5-ijMq2DXm9fcefC_Y4ryNM3d4deZpi_u6EOIjmZ6K-qp4tNwsHq2Y81xbr42aczVvyuR3xZiT_h)|||
|2023|arXiv|[Geometric Rectification of Creased Document Images based on Isometric Mapping](https://arXiv.org/abs/2212.08365)|||
|2023|IJDAR|[Adaptive Dewarping of Severely Warped Camera-captured Document Images Based on Document Map Generation](https://link.springer.com/content/pdf/10.1007/s10032-022-00425-4.pdf?pdf=button)|||
|2023|TMM|[Deep Unrestricted Document Image Rectification](https://arXiv.org/abs/2304.08796)|[Code](https://github.com/fh2019ustc/DocTr-Plus)|
|2023|IJDAR|[Inv3D: A High-resolution 3D Invoice Dataset for Template-guided Single-image Document Unwarping](https://link.springer.com/article/10.1007/s10032-023-00434-x)|[Code](https://github.com/FelixHertlein/inv3d-model)||
|2023|arXiv|[DocAligner: Annotating Real-world Photographic Document Images by Simply Taking Pictures](https://arXiv.org/pdf/2306.05749.pdf)|[Code](https://github.com/ZZZHANG-jx/DocAligner)||
|2023|arXiv|[MataDoc: Margin and Text Aware Document Dewarping for Arbitrary Boundary](https://arXiv.org/pdf/2307.12571)|||
|2023|ICCVW|[Template-guided Illumination Correction for Document Images with Imperfect Geometric Reconstruction](https://openaccess.thecvf.com/content/ICCV2023W/NIVT/papers/Hertlein_Template-Guided_Illumination_Correction_for_Document_Images_with_Imperfect_Geometric_Reconstruction_ICCVW_2023_paper.pdf)|[Code](https://github.com/FelixHertlein/illtrtemplate-model)||
|2023|ICCV|[Foreground and Text-lines Aware Document Image Rectification](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Foreground_and_Text-lines_Aware_Document_Image_Rectification_ICCV_2023_paper.pdf)|[Code](https://github.com/xiaomore/document-image-dewarping)||
|2023|TAI|[Appearance Enhancement for Camera-captured Document Images in the Wild*](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10268585)|[Code](https://github.com/ZZZHANG-jx/GCDRNet)||
|2023|ACM TOG|[Layout-Aware Single-Image Document Flatening](https://dl.acm.org/doi/pdf/10.1145/3627818)|[Code](https://github.com/BunnySoCrazy/LA-DocFlatten)|[Link](https://github.com/BunnySoCrazy/LA-DocFlatten)|
|2023|WACV|[DocReal: Robust Document Dewarping of Real-Life Images via Attention-Enhanced Control Point Prediction](https://openaccess.thecvf.com/content/WACV2024/papers/Yu_DocReal_Robust_Document_Dewarping_of_Real-Life_Images_via_Attention-Enhanced_Control_WACV_2024_paper.pdf)|[Code](https://github.com/irisXcoding/DocReal)||
|2023|TCSVT|[Rethinking Supervision in Document Unwarping: A Self-consistent Flow-free Approach](https://ieeexplore.ieee.org/abstract/document/10327775)|||
|2023|SIGGRAPH|[UVDoc: Neural Grid-based Document Unwarping](https://dl.acm.org/doi/fullHtml/10.1145/3610548.3618174)|[Code](https://github.com/tanguymagne/UVDoc)||
|2023|arXiv|[Polar-Doc: One-Stage Document Dewarping with Multi-Scope Constraints under Polar Representation](https://arXiv.org/abs/2312.07925)|||
|2024|ACM MM|[Document Registration: Towards Automated Labeling of Pixel-Level Alignment Between Warped-Flat Documents](https://openreview.net/pdf?id=EjjY5yJzQG)|||
|2024|AAAI|[DocNLC: A Document Image Enhancement Framework with Normalized and Latent Contrastive Representation for Multiple Degradations](https://ojs.aaai.org/index.php/AAAI/article/view/28366)|[Code](https://github.com/RylonW/DocNLC)||
|2024|CVPR|[DocRes: a generalist model toward unifying document image restoration tasks](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_DocRes_A_Generalist_Model_Toward_Unifying_Document_Image_Restoration_Tasks_CVPR_2024_paper.pdf)|[Code](https://github.com/ZZZHANG-jx/DocRes)||
|2025|IJCV|[DocScanner: Robust Document Image Rectification with Progressive Learning](https://drive.google.com/file/d/1mmCUj90rHyuO1SmpLt361youh-07Y0sD/view?usp=share_link)|[Code](https://github.com/fh2019ustc/DocScanner)|[Link](https://drive.google.com/drive/folders/1QBe26xJwIl38sWqK2ZE9ke5nu0Mpr4dW?usp=sharing)|
|2025|WACV|[DocMatcher: Document Image Dewarping via Structural and Textual Line Matching](https://openaccess.thecvf.com/content/WACV2025/papers/Hertlein_DocMatcher_Document_Image_Dewarping_via_Structural_and_Textual_Line_Matching_WACV_2025_paper.pdf)|[Code](https://github.com/FelixHertlein/doc-matcher)||
|2025|CVPR|[Document Image Rectification using Stable Diffusion Transformer](https://openaccess.thecvf.com/content/CVPR2025W/WiCV/papers/Kumari_Document_Image_Rectification_using_Stable_Diffusion_Transformer_CVPRW_2025_paper.pdf)|||
|2025|arXiv|[DvD: Unleashing a Generative Paradigm for Document Dewarping via Coordinates-based Diffusion Model](https://arxiv.org/abs/2505.21975)|||


- The ***results*** are the rectified images on the [DocUNet Benchmark Dataset](https://www3.cs.stonybrook.edu/~cvl/docunet.html).
- The "*" means that the work involves the illumination correction for document images.

# Datasets

|***Year***|***Venue***|***Title***|***Type***|***Link***|
|----|----|-----|----|----|
|2018|CVPR|[DocUNet: Document Image Unwarping via A Stacked U-Net](https://openaccess.thecvf.com/content_cvpr_2018/papers/Ma_DocUNet_Document_Image_CVPR_2018_paper.pdf)|Real|[Dataset](https://www3.cs.stonybrook.edu/~cvl/docunet.html)|
|2019|TOG|[Document Rectification and Illumination Correction using a Patch-based CNN](https://arXiv.org/pdf/1909.09470.pdf)|Synthetic|[Dataset](https://github.com/xiaoyu258/DocProj)|
|2019|ICCV|[DewarpNet: Single-Image Document Unwarping With Stacked 3D and 2D Regression Networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Das_DewarpNet_Single-Image_Document_Unwarping_With_Stacked_3D_and_2D_Regression_ICCV_2019_paper.pdf)|Synthetic|[Dataset](https://github.com/fh2019ustc/doc3D-dataset)|
|2020|DAS|[Dewarping Document Image by Displacement Flow Estimation with Fully Convolutional Network](https://arXiv.org/pdf/2104.06815.pdf)|Synthetic|[Dataset](https://github.com/gwxie/Distorted-Image-With-Flow)|
|2021|ICDAR|[Document Dewarping with Control Points](https://arXiv.org/pdf/2203.10543.pdf)|Synthetic|[Dataset](https://github.com/gwxie/Synthesize-Distorted-Image-and-Its-Control-Points)|
|2022|CVPR|[Fourier Document Restoration for Robust Document Dewarping and Recognition](https://openaccess.thecvf.com/content/CVPR2022/papers/Xue_Fourier_Document_Restoration_for_Robust_Document_Dewarping_and_Recognition_CVPR_2022_paper.pdf)|Real|[Dataset](https://sg-vilab.github.io/event/warpdoc/)|
|2022|SIGGRAPH|[Learning From Documents in the Wild to Improve Document Unwarping](https://dl.acm.org/doi/pdf/10.1145/3528233.3530756)|Real|[Dataset](https://github.com/cvlab-stonybrook/PaperEdge)|
|2022|ECCV|[Geometric Representation Learning for Document Image Rectification](https://arXiv.org/pdf/2210.08161.pdf)|Real|[Dataset](https://drive.google.com/drive/folders/1yySouQQ3BlH7OjnUhq4CLuvpX2KXtifX?usp=sharing)|
|2022|ICBD|[ADIU: An Antiquarian Document Image Unwarping Dataset](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10020521)|Both||
|2023|IJDAR|[Adaptive Dewarping of Severely Warped Camera-captured Document Images Based on Document Map Generation](https://link.springer.com/content/pdf/10.1007/s10032-022-00425-4.pdf?pdf=button)|Real|[Dataset](https://github.com/NachappaCH/Dewarping-Dataset-Annotations)|
|2023|TMM|[Deep Unrestricted Document Image Rectification](https://arXiv.org/abs/2304.08796)|Real|[Dataset](https://github.com/fh2019ustc/DocTr-Plus)|
|2023|SIGGRAPH|[UVDoc: Neural Grid-based Document Unwarping](https://arXiv.org/pdf/2302.02887.pdf)|Synthetic|[Dataset](https://github.com/tanguymagne/UVDoc-Dataset)|
|2023|arXiv|[DocAligner: Annotating Real-world Photographic Document Images by Simply Taking Pictures](https://arXiv.org/pdf/2306.05749.pdf)|Real|[Dataset](https://github.com/ZZZHANG-jx/DocAligner)|
|2023|IJDAR|[Inv3D: A High-resolution 3D Invoice Dataset for Template-guided Single-image Document Unwarping](https://link.springer.com/article/10.1007/s10032-023-00434-x)|Synthetic|[Dataset](https://felixhertlein.github.io/inv3d/#Downloads)|

# Demos
|***Year***|***Name***|***Host***|***Type***|
|----|-----|----|----|
|2019|[DewarpNet: Single-Image Document Unwarping With Stacked 3D and 2D Regression Networks](https://sagniklp.github.io/dewarpnet-demo/)|  | Online Demo |
|2021|[DocTr: Document Image Transformer for Geometric Unwarping and Illumination Correction](https://huggingface.co/spaces/HaoFeng2019/DocTr)| huggingface | Online Demo |
|2022|[DocGeoNet: Geometric Representation Learning for Document Image Rectification](https://huggingface.co/spaces/HaoFeng2019/DocGeoNet)| huggingface | Online Demo |
|2022|[dewarp](https://www.textin.com/experience/dewarp)| textin | Online Demo |
|2023|[Deep Unrestricted Document Image Rectification](https://demo.doctrp.top/)| self-hosted | Online Demo |
|2023|[Inv3D: GeoTrTemplate & IllTrTemplate](https://felixhertlein.de/docrefine/home)| self-hosted | Online Demo |


## Acknowledgment
* This repository is scheduled to be updated regularly in accordance with schedules of major AI Conferences and Journals.
