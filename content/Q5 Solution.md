---
title: High School Question 2 Solution
---
>$$ \\ $$
>
>$$
>\text{Find the derivative of } y^{x}=x^{y} \text{.}
>$$
>
>$$ \\ $$

$$ \\ $$
Write the problem out:

$$
\frac{d}{dx}\left(y^{x}=x^{y}\right)
$$

Take the natural logarithm of both sides in order to apply [[The Power Rule of Logarithms|the power rule of logarithms]].

$$
\frac{d}{dx}\big(\ln\left(y^{x}\right)=\ln\left(x^{y}\right)\big)
$$

Apply [[The Power Rule of Logarithms|the power rule of logarithms]].

$$
\frac{d}{dx}\big(x\ln\left(y\right)=y\ln\left(x\right)\big)
$$

Apply [[The Product Rule of Derivatives|the product rule of derivatives]].

$$
\frac{d}{dx}\left(x\right) \cdot \ln\left(y\right) + x \cdot \frac{d}{dx}\big(\ln\left(y\right)\big)= \frac{d}{dx}\left(y\right) \cdot \ln\left(x\right)+ y \cdot \frac{d}{dx}\big(\ln\left(x\right)\big)
$$

Differentiate.

$$
1 \cdot \ln\left(y\right) + x \cdot \frac{1}{y} \cdot \frac{dy}{dx} = 1 \cdot \frac{dy}{dx} \cdot \ln\left(x\right) + y \cdot \frac{1}{x}
$$

Simplify and solve for $\frac{dy}{dx}$.

$$
\ln\left(y\right) + \frac{x}{y} \cdot \frac{dy}{dx} = \frac{dy}{dx} \cdot \ln\left(x\right) + \frac{y}{x}
$$

$$
\frac{x}{y} \cdot \frac{dy}{dx} - \frac{dy}{dx} \cdot \ln\left(x\right) = \frac{y}{x} - \ln\left(y\right)
$$

$$
\frac{dy}{dx} \cdot \left(\frac{x}{y} - \ln\left(x\right)\right)= \frac{y}{x} - \ln\left(y\right)
$$

$$
\frac{dy}{dx}= \frac{\frac{y}{x} - \ln\left(y\right)}{\frac{x}{y} - \ln\left(x\right)}
$$

Simplify the fraction.

$$
\begin{gather*}
\frac{dy}{dx}= \frac{\frac{y}{x} - \ln\left(y\right)}{\frac{x}{y} - \ln\left(x\right)} \cdot \frac{xy}{xy} \\ \\
\frac{dy}{dx}= \frac{xy\left(\frac{y}{x} - \ln\left(y\right)\right)}{xy\left(\frac{x}{y} - \ln\left(x\right)\right)} \\ \\
\frac{dy}{dx}= \frac{y^{2} - xy\ln\left(y\right)}{x^{2} - xy\ln\left(x\right)}
\end{gather*}
$$

$$ \\ $$
Therefore, the derivative of $y^{x}=x^{y}$ is $\frac{y^{2} - xy\ln\left(y\right)}{x^{2} - xy\ln\left(x\right)}$.