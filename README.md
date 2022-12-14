# RhythmDancer
3D dance generation

<p float="left">
	<img src="https://github.com/Ryan00618/RhythmDancer/blob/main/gif/show_git.gif" width="400" /> <img src="https://github.com/Ryan00618/RhythmDancer/blob/main/gif/demo0.gif" width="400" /> 
	</p>

[[Video Demo on YouTube]](https://youtu.be/bytDZc53TQE)

## Abstract

3D dance generation is an important research direction that will benefit the development of video-related applications and is crucial to the currently rapidly developing metaverse. Previous work usually treats this task simply as a sequence generation task, but there are two serious problems in the process of generating dance sequences: (1) it is difficult for dance movements to perfectly match the beat of music, (2) in the generation of dance sequences, there are two serious problems. When performing dance sequences, the quality of the generated dance sequences is difficult to guarantee over time. Often, the learning of dance starts with learning core dance moves and then connecting those moves together to form a beautiful dance. Inspired by this, this paper proposes a novel generative 3D dance framework to address the above problems. The model first uses VQ-VAE-2 to perform hierarchical encoding and quantization on dance, which effectively improves the quality of dance generation. Then the core dance movement code on the rhythm point is used to establish the movement transformation map, which ensures the fit of the generated dance movement and the music rhythm, and increases the diversity of dance movements. To make the connected actions between the core dance moves smooth and natural, we propose a pose-interpolated network to learn the transition actions between key moves. Finally, we have proved through experiments that this scheme is superior to existing schemes, avoids the instability and uncontrollable problems of long sequence generation, achieves a high degree of fit between dance movements and music rhythm, and achieves the of state-of-the-art performance.
