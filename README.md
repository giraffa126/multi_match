# multi_match
dmdict
======
������Ӧ�ó���
--------------
��lib���е�ul_dictmatch������python��װ���Ӷ��ܷ�����ж�ģƥ�䡣

ʹ�÷���
--------
���Բο�test_dm.py����ʹ��

    ����һ���ʵ�
        import dmdict
        d = dmdict.DMSearchDict()

    ��Ӵ���
        d.add( lemma )
        d.add( lemma, prop )

    ĸ������
        for lemma, begin, length, prop in d.find( long_text ):
            # do something.

    ���л�
        d.save(output_filename)
        d.load(input_filename)

