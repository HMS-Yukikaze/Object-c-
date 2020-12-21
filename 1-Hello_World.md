# 第一个Object C程序  
***eg:***<br>

	//First Object-c code
	#import <Fundation/Fundation.h>  
	int main(int argc , char * argv[]){  		
		NSLog(@"Hello World");  		
		return 0;  
	}
		
## 1.程序结构<br>
- 预处理命令<br>
		**\#\import \<\Fundation/Fundation.h\>\** 是一个预处理程序命令，它告诉Objective-C编译器在进行实际编译之前包含Foundation.h头文件<br>
- 接口<br>
	
		@interface SampleClass:NSObject<br>
		(void)sampleMethod;<br>
		@end<br>
		
创建了`SampleClass`接口，此接口继承于`NSObject`

- 实现/方法<br>
	
		@implementation SampleClass</br>
		(void)sampleMethod {<br>
		NSLog(@"Hello, World! \n");<br>
		}<br>

**@implementation SampleClass{......}** 实现了 **SampleClass**接口,**(void)sampleMethod**实现了**sampleMethod**方法<br>

- 变量<br>


- 声明和表达<br>


- 注释<br>
**单行注释：** ``//``<br>
**多行注释：** ``/******/``<br>


