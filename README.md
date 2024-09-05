# sparse-identification-of-non-linear-dynamics

involves extracting governing equations of physical systems from noisy experimental data following https://doi.org/10.1073/pnas.151738411; Discovering governing equations from data by sparse identification of nonlinear dynamical systems; Steven L. Bruntona,1, Joshua L. Proctorb, and J. Nathan Kutzc. 


the dynamics of a chaotic lorenz system has been derived from the generated data at varied noise amplitudes. An FFT based thresholding approach has been used to denoise the derivative, other possible methods include variation regularization and singular value optimal thresholding.

results were in accordance to the authors work, accurate dynamics of the Lorenz attractor were recovered both for a noisy data as well as a stochastic lorenz attractor, i e., noise being inherent in the system. although the long term dynamics are difficult to reproduce as the system is highly chaotic and is not a short coming of the method itself.
