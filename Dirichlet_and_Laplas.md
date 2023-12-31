Для решения задачи Дирихле для уравнения Лапласа в круге можно использовать метод разделения переменных, который состоит из следующих шагов:

1. Записываем уравнение Лапласа в полярных координатах:
$$\frac{1}{r}\frac{\partial}{\partial r}(r\frac{\partial u}{\partial r}) + \frac{1}{r^2}\frac{\partial^2 u}{\partial \theta^2}=0.$$

2. Представляем решение в виде произведения функций $u(r,\theta)=R(r)\Theta(\theta)$.

3. Подставляем представление решения в уравнение Лапласа и делим на $u(r,\theta)$:
$$\frac{1}{R}\frac{d}{dr}(r\frac{d R}{dr}) + \frac{1}{\Theta}\frac{d^2 \Theta}{d \theta^2}=0.$$

4. Решаем два уравнения:
$$\frac{1}{R}\frac{d}{dr}(r\frac{d R}{dr})+m^2\frac{1}{r^2}R=0,$$
$$\frac{d^2\Theta}{d\theta^2}+m^2\Theta=0,$$
где $m$ - натуральное число.

5. Решаем уравнение для $R$ методом Фробениуса:
$$R(r)=c_1r^m+c_2r^{-m}.$$

6. Учитывая условие Дирихле, закрепляющее значение решения на границе круга $u(R,\theta)=f(\theta)$, определяем константы $c_1$ и $c_2$:
$$R(R)=c_1R^m+c_2R^{-m}=f(\theta).$$

7. Решаем уравнение для $\Theta$:
$$\Theta(\theta)=c_3\cos(m\theta)+c_4\sin(m\theta).$$

8. Общее решение уравнения Лапласа имеет вид:
$$u(r,\theta)=\sum_{m=1}^{\infty}(a_mr^m+b_mr^{-m})\cos(m\theta)+\sum_{m=1}^{\infty}(c_mr^m+d_mr^{-m})\sin(m\theta).$$

9. Определяем коэффициенты $a_m$, $b_m$, $c_m$ и $d_m$ из условия Дирихле и полученного общего решения.

10. Окончательное решение имеет вид:
$$u(r,\theta)=\sum_{m=1}^{\infty}\left(\frac{R^m}{R^n}+\frac{R^{-m}}{R^n}\right)\left(c_m\cos(m\theta)+d_m\sin(m\theta)\right).$$

Таким образом, решение задачи Дирихле для уравнения Лапласа в круге сводится к решению системы уравнений, нахождению коэффициентов и суммированию рядов.
