## Center of Gravity of Minor Segment

<p align="center">
  <img width="250" src="https://user-images.githubusercontent.com/86240528/213643072-f8287386-5448-4017-89d1-cafa9dd66eec.jpg">
  <br />
  
</p>

Consider a strip PQ

Assuming $m =$ mass per unit area

Mass element of strip; $dm =$ mass per unit area $\times$ area of strip

Length of PQ = $2x$ <br>
Breadth of PQ = $δy$

$$\Rightarrow d m=m \times 2 x \times \delta y$$

$$\Rightarrow d m=2mx\delta y$$

Equation of Circle $\Rightarrow x^2+y^2=r^2$

$$\Rightarrow x=\sqrt{a^2-y^2}$$

$$\Rightarrow d m=2m\sqrt{r^2-y^2}\delta y$$

Center of Gravity, 
$$\bar{y}=\frac{\int y d m}{\int d m}$$

Integration limits will vary from point M to C in $y$ direction

$OC = r$ and From $\triangle A O M$, $OM = r\cos (\theta/2)$

$$\Rightarrow \bar{y}=\frac{\int_{O M}^{O C} y d m}{\int_{O M}^{O C} d m}=\frac{\int_{r \cos \theta}^r y 2 m \sqrt{r^2-y^2} d y}{\int_{r \cos \theta}^r 2 m \sqrt{r^2-y^2} d y}=\frac{\int_{r \cos \theta}^r y  \sqrt{r^2-y^2} d y}{\int_{r \cos \theta}^r  \sqrt{r^2-y^2} d y}$$

Let  $I_1=\int_{r \cos \theta}^{r} y \sqrt{r^2-y^2} \mathrm{~d} y$ and  $I_2=\int_{r \cos \theta}^r  \sqrt{r^2-y^2} \mathrm{~d} y$
___

$$I_1=\int_{r \cos \theta}^{r} y \sqrt{r^2-y^2} \mathrm{~d} y$$

Substituting $r^2-y^2=t$
$$ydy=-\frac{dt}{2}$$

$$I_1=\int y \sqrt{r^2-y^2} \mathrm{~d} y=\int \sqrt{t}(-\frac{\mathrm{~d} t}{2}) = -\frac{1}{3}t^{3/2}+constant = -\frac{1}{3}(r^2-y^2)^{3/2}+constant$$

$$I_1=\int_{r \cos \theta}^{r} y \sqrt{r^2-y^2} \mathrm{~d} y=-\frac{1}{3}\left[(r^2-r^2)^{3/2}-(r^2-r^2 \cos^2 \theta)^{3/2}\right]$$

$$I_1=\frac{1}{3} r^3 \sin^3 \theta$$
___


$$I_2=\int_{r \cos \theta}^{r}  \sqrt{r^2-y^2} \mathrm{~d} y$$

Taking constat function 1 as the second function and integrating by parts, we have

$$I_2=y\sqrt{r^2-y^2}-\int \frac{1}{2} \frac{-2y}{\sqrt{r^2-y^2}}y \mathrm{~d} y$$

$$I_2=y\sqrt{r^2-y^2}-\int  \frac{-r^2+r^2-y^2}{\sqrt{r^2-y^2}} \mathrm{~d} y$$

$$I_2=y\sqrt{r^2-y^2}-\int  \frac{r^2-y^2}{\sqrt{r^2-y^2}} \mathrm{~d} y + \int  \frac{r^2}{\sqrt{r^2-y^2}} \mathrm{~d} y$$

$$I_2=y\sqrt{r^2-y^2}-\int  \sqrt{r^2-y^2} \mathrm{~d} y + \int  \frac{r^2}{\sqrt{r^2-y^2}} \mathrm{~d} y$$

$$I_2=y\sqrt{r^2-y^2}-I_2  + \int  \frac{r^2}{\sqrt{r^2-y^2}} \mathrm{~d} y$$

$$2I_2=y\sqrt{r^2-y^2} +r^2 \int  \frac{1}{\sqrt{r^2-y^2}} \mathrm{~d} y$$

Substituting $y=r \sin \theta$,   $\mathrm{~d}y=r\cos\theta \mathrm{~d}\theta$

$$\int  \frac{1}{\sqrt{r^2-y^2}} \mathrm{~d} y=\int \frac{r\cos\theta}{\sqrt{r^2-r^2\sin^2\theta}} \mathrm{~d} \theta=\int\mathrm{~d} \theta=\theta + constant = \sin^{-1}\frac{y}{r} + constant$$

$$\Rightarrow I_2=\frac{y}{2}\sqrt{r^2-y^2} +\frac{r^2}{2}\sin^{-1}\frac{y}{r} + constant$$

$$I_2=\int_{r \cos \theta}^{r}  \sqrt{r^2-y^2} \mathrm{~d} y=\left[\frac{r}{2}\sqrt{r^2-r^2}+\frac{r^2}{2}\sin^{-1}\frac{r}{r}\right]-\left[\frac{r\cos\theta}{2}\sqrt{r^2-r^2\cos^2\theta}+\frac{r^2}{2}\sin^{-1}\frac{r\cos\theta}{r}\right]$$

$$I_2=\int_{r \cos \theta}^{r}  \sqrt{r^2-y^2} \mathrm{~d} y=\left[0+\frac{r^2}{2}\sin^{-1}(1)\right]-\left[\frac{r^2\cos\theta\sin\theta}{2}+\frac{r^2}{2}\sin^{-1}\left(\sin\frac{\pi}{2}-\theta\right)\right]$$

$$I_2=\int_{r \cos \theta}^{r}  \sqrt{r^2-y^2} \mathrm{~d} y=\frac{r^2}{2}\frac{\pi}{2}-\frac{r^2\sin2\theta}{4}-\frac{r^2\pi}{4}+\frac{r^2\theta}{2}$$

$$I_2=\frac{r^2}{4}\left[2\theta-\sin2\theta\right]$$
___

$$\Rightarrow \bar{y}=\frac{I_1}{I_2}=\frac{\frac{1}{3} r^3 \sin^3 \theta}{\frac{r^2}{4}\left[2\theta-\sin2\theta\right]}$$

$$\bar{y}=\frac{4r\sin^3\theta}{3(2\theta-\sin2\theta)}$$

<p align="center">
  <img width="250" src="https://user-images.githubusercontent.com/86240528/213643282-f942c1ec-1dc6-4cb6-a9bc-7eb7c6148ce5.jpg">
  <br />
  
</p>

___
