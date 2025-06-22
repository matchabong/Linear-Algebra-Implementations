# Linear Algebra Projects:
This repository showcases a series of projects completed as part of a Linear Algebra course, demonstrating practical applications of core concepts in areas such as data science, computer graphics, and error correction. All projects are implemented in Python and presented as Jupyter Notebooks, utilizing common scientific computing and visualization libraries.

## HW1: Markov Chains 

This project demonstrates the practical application of Markov chains in generative modeling, specifically for text generation. It showcases the implementation of N-gram models to predict sequential data, highlighting how statistical relationships between elements can be used to construct new sequences. The project further explores the theoretical underpinnings of Markov chains by demonstrating how to numerically compute and understand the significance of stationary distributions, which represent the long-term behavior of a stochastic system. It also shows the capability of leveraging and critically evaluating information from Large Language Models (LLMs) for advanced topic research and verification.

1. Programming Language: Python
2.  Key Libraries/Tools: numpy for numerical operations, matplotlib for potential visualizations, Jupyter Notebook for interactive development and presentation.
3. Concepts Highlighted: Stochastic processes, N-gram models, transition matrices, stationary distributions, numerical methods for linear systems, LLM interaction.
   
## HW2: Error Correction Codes (ECC)

This project displays a robust implementation of the Hamming (7,4) error correction code, illustrating how redundant bits can be systematically added to data to enable the detection and correction of single-bit errors. It clearly demonstrates the application of 0-1 vector space algebra and linear transformations for encoding messages. Furthermore, the project highlights the powerful role of a matrix's null space in pinpointing error locations, providing a concrete example of how abstract linear algebra concepts are used to ensure data integrity in digital systems.

1. Programming Language: Python
2. Key Libraries/Tools: numpy for matrix operations (specifically with binary arithmetic emulation), Jupyter Notebook for interactive development.
3. Concepts Highlighted: Error correction codes (Hamming code), finite fields (F 
2), vector spaces, linear transformations, matrix multiplication, null space, error detection and correction algorithms.

## HW3: Flat Shading

This project showcases the fundamental principles of 3D computer graphics rendering through flat shading. It effectively demonstrates the process of taking a 3D model (from an .obj file) and calculating its visual appearance based on simple lighting models (ambient and specular). Key aspects displayed include the geometric computations necessary for 3D rendering, such as determining viewer direction, calculating surface normals for triangular faces, and identifying visible surfaces. It also illustrates how basic lighting equations are applied to determine polygon intensity, providing a foundational understanding of how 3D objects are illuminated in a virtual environment. The project further extends to exploring the nuances of vertex normals for smoother shading, showcasing an understanding of more advanced rendering concepts.

1. Programming Language: Python
2. Key Libraries/Tools: numpy for vector and matrix operations, matplotlib.pyplot and mpl_toolkits.mplot3d.art3d for 3D visualization and rendering, custom .obj file parser.
3.  Concepts Highlighted: 3D graphics rendering, flat shading, ambient and specular lighting, vector geometry (dot products, cross products, normalization), surface normals, vertex normals, 3D model parsing (.obj format).

## HW4: Image Compression 

This project demonstrates the efficacy of Singular Value Decomposition (SVD) as an image compression technique. It visually and quantitatively illustrates how an image, represented as a matrix, can be approximated using a reduced number of singular values, thereby achieving compression. The project clearly displays the trade-offs between compression ratio and image quality (quantified by average relative difference), providing empirical evidence of SVD's performance. Furthermore, it highlights the analytical understanding of how an image's inherent characteristics and the distribution of its singular values influence its compressibility, identifying which parts of an image are most affected by the compression process.

1. Programming Language: Python
2. Key Libraries/Tools: numpy for SVD and matrix operations, matplotlib.pyplot for image display and singular value plotting, imageio.v2 for image loading.
3. Concepts Highlighted: Image processing, Singular Value Decomposition (SVD), dimensionality reduction, data compression, compression ratio, error metrics (average relative difference), spectral analysis of images
