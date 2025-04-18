# Abstract TAL

def fx $$\ell:\mathbb R^2\rightarrow \mathbb R^1$$

def value $$\ell f=\ell(f_0,f_1)$$

def mark (boundedness req) $$\ell^\dagger f = \ell^{\dagger}(f_0,f)$$

def $$\ell z = \ell f \dagger \ell^\dagger z$$

def $$\ell z = \ell^{\dagger} z_0^{-1}\circ f^{-1}\circ\ell f_0\circ f_0$$

def Macro trace: $$\Delta_{\ell} \circ t=\sum_{i=1}^{\text{Length}[t]}e_i\cdot \ell^{\dagger} t_i,\text{Where}[\ell^n\rightarrow \ell^n]$$

def Macro path: $$\Delta_{\digamma(\rho)}\circ \ell t=\sum_{i=1}^{\text{Length}[\rho]-1} e_i\cdot\ell (\rho_i,\rho_{i+1})$$ , $$\text{Where}[\ell^1\rightarrow \ell^n,\rho_1=t,\rho_{\text{Length}[\rho]}=\ell t\circ t]$$


