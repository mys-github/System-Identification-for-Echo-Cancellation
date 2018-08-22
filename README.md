# Adaptive Algorithms for Echo Cancellation
    
System Identification/Modeling for Echo Cancellation:   In this application an adaptive filter to identify the impulse response of the path between the source from which the echo originates adn the point where it appears. The output of the adaptive filter, which is an estimate of the echo signal, can be used to cancel the undesirable echo. 
In my Project I simulated an echo by feeding unit variance white Gaussian noise through a system H(z) (which can be considered a as a channel) the output from this system is fed into the plant we want to estimated W(z). The plant output is then contaminated with an additive white Gaussian Noise with variance sigma^2
