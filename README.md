# for-循环变种——新学的，再复习一遍


变种一：

int main()
{
	for (; ;)
	{
		printf("hehe\n");
	}
	return 0;
}
//无数个 hehe 。（死循环）
//1、for循环的初始化、调整、判断可以省略，但是；for循环的额，判断部分如果被省略，那判断条件就恒为正（真）
//2、不是特别熟练，别省略




int main()
{
	int i = 0;
	int j = 0;
	for (; i < 10; i++)
	{
		for (; j < 10; j++)
		{
			printf("hehe\n");
		}
	}
	return 0;
}

//循环10次




int main()
{
	int i = 0;
	int j = 0;
	for (i = 0; i < 10; i++)
	{
		for (j = 0; j < 10; j++)
		{
			printf("hehe\n");
		}
		//10*10=100	、循环了100次
	}
	return 0;
}

变种二：
int main()
{
	int x, y;
	for (x = 0, y = 0; x < 2 && y < 5; ++x, y++)
	{
		printf("hehe\n");
	}

	return 0;

}

