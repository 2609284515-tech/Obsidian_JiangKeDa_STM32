需要[[开启USART]]
```
//串口重定向printf
int fputc(int ch, FILE *f)
{
	Serial_SendByte(ch);
	return ch;
}
```