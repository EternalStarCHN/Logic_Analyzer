Chinese:
֧�֣�Linux2.6.18 ~3.x
1����װ������
	A������driverĿ¼��ִ��
			# make
			# insmod ch341_pis.ko
2��ִ��Ӧ�ò��Գ���
	A������demoĿ¼��ִ��
			# make
		 ����DEMO��DEMO_GUI��ִ���ļ���
	B������./DEMO�������ն˲��Գ���
		 ����./DEMO_GUI������gtk�������
		
English:
Support: Linux kernel 2.6.28 ~ 3.x
1��install driver
		A��get into ch34x_pis/driver, execute
				# make
				# insmod ch341_pis.ko
2��test the validity of driver
		A�� enter demo, execute
				# make
				Then, in this catalogue you can find two executable files, one: DEMO the other: DEMO_GUI.
		B�� execute DEMO
				# ./DEMO
		C�� execute DEMO_GUI
				# ./DEMO_GUI
				this depens on gtk+-2.0 lib. So ensure your system have this lib.