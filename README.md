һ����Ŀ"�決��"��������


### ��Ŀ����: 
- ��Ŀ:   npm run dev  : 
- ����: cd admin    = >    node server.js

������ĿĿ¼
npm install // ��װ����

npm run dev����Node Server���ṩAPI�ӿ�
cd admin 
node server.js// ����webpack-dev-server��ʵʱ����ǰ�˴��룬���������Ҫ���µ�������
�ȴ� npm run dev���н����󣬻��Զ����������http://localhost:9333/#/



### 1������Ŀ�ǻ���create-react-app���ּܴ��

�Ѱ�װģ��
- react
- react-dom
- webpack������һ�ף�babelϵ�С�css������ϵ�С�һЩ�ϲ�ѹ���Ĳ�����Զ���������Ԥ���Ĳ��...
- ...

�������ǻ��õ���ģ�鵫��û��Ĭ�ϰ�װ��
- redux / react-redux
- react-router-dom
- prop-types
- less / less-loader  ���޸�һ��webpack�����ã�
- axios
- redux�м��
- ...

# Ŀ¼�ṹ
E:.
��  index.js            //������ļ�
��
����api                 //API�������˵�ǰ��Ŀ�����жԺ�̨���������󷽷�
����common               //����css�ļ�,js�ļ�,��ͼƬ��
��  ����css
��  ����image
��  ����js
����component            //��Ź������
��      Tab.js
��
����container            //���ҳ�漶���
��      Home.js
��
����store                 //rudux
    ��  action-types.js
    ��  index.js
    ��
    ����action
    ��      index.js
    ��
    ����reducer
            index.js
