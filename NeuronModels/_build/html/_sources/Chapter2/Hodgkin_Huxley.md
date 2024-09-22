# Hodgkin–Huxley model

The dynamics of the HH model is given by

$$ C \frac{dV}{dt} = I_{\text{Ext}} -  g_{\text{Na}}  m^3 h (V-E_{\text{Na}}) - g_{\text{K}}  n^4 (V-E_{\text{K}}) -g_{\text{Leak}} (V-E_{\text{Leak}}) ,$$

where $m,n,$ and $k$ are the gating varibales that model the probability that a channel is open at a given moment in time, $g_{Na}$, $g_{K}$ and $g_{\text{Leak}$ are the conductance. The dynamics of the gating variables are defined by


$$
\frac{dn}{dt} = \alpha_n (V)(1-n) - \beta_n(V)n
$$




$$
\dot{x}=-{1\over\tau_{x}(u)}[x-x_{0}(u)],
$$

where $x$ stands for $m,n, \text{or} h$ and  $\tau(u)$ is the time constant. 
