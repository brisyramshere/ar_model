## ���ܽ���

1. zx_fft.c/hʵ����FFT���ܣ�����ʵ��FFT��
2. mem_alloc.c/h�а������ڴ�������ܣ��ο�uCOS II��ֲ����������Ƕ��ʽӦ�ã�ar_model.c�жദ���ã�
3. zx_correl.c/h�ö���ʵ���˻���أ������ʵ�ַ�����ʵЧ�ʺܵͣ�����[Github/FFT]�ṩ��ʹ��FFT���㻥��غ�����C���룩
4. ar_model.c/h��ʹ��Levinson������FFTʵ����PSD����źŵĹ����׹���
5. test_mem_alloc.c/h�ṩ��һ��ʹ�òο�ʵ��

��������C��Matlabʵ����PSD�����׵ļ��㣬��ͨ��Matlab������Matlab��C�������ĶԱȣ�

![](./signal.png)
![](./psd-matlab-c.png)

## ʹ�÷���

- ����wave_to_c.m����ѡ��*.wav�ļ���ִ�к���Ƶ����д�뵽testcase.hͷ�ļ��ļ�
- ִ��Makefile����C�������н�ִ�н���ض�λ����a.txt�ļ���gcc�汾3.4.4��
    ```
	make
	make run
    ```
- ִ��disp_result.m�鿴C����Ľ����Matlab���㹦���׽���ĶԱ�


## ������Ϣ

<xiahouzuoxin@163.com>

University of Science and Technology Beijing(USTB), MICL.



[Github/FFT]:https://github.com/xiahouzuoxin/fft