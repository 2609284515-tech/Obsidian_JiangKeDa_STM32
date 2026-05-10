需要[[OC初始化]]
```
//改CCR
void PWM_SetCompare1(uint16_t Compare)
{
	TIM_SetCompare1(TIM2, Compare);
}
```