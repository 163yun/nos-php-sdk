Netease Object Storage(NOS) PHP SDK
- V1.0.0
�ṩ���½ӿڣ�
(1)Ͱ�����ӿ�
	createBucket ------ �½�Ͱ
	deleteBucket ------ ɾ��Ͱ
	doesBucketExist ------ �ж�Ͱ�Ƿ����
	putBucketAcl ------ ����Ͱ��acl
	getBucketAcl ------ ��ȡͰ��acl
	listBuckets ------ �оٵ�ǰ�û����е�Ͱ
	getBucketLocation ------ ��ȡͰ��location
(2)��������ӿ�
	putObject ------ �ϴ��ַ�������
	uploadFile ------ �ϴ��ļ�
	doesObjectExist ------ �ж϶����Ƿ����
	GetObjectMeta ------ ��ȡ����Ԫ��Ϣ
	copyObject ------ ���ƶ���
	moveObject ------ �ƶ�����
	deleteObject ------ ɾ������
	deleteObjects ------ ����ɾ������
	getObject ------ ��ȡ����
(3)�����ֿ�����ӿ�
	initiateMultipartUpload ------ ��ʼ���ֿ��ϴ�
	generateMultiuploadParts ------ �����ϴ��ֿ��б�
	uploadPart ------ �ϴ��ֿ�
	completeMultipartUpload ------ ��ɷֿ��ϴ�
	listParts ------ �г������ϴ��ķֿ�
	abortMultipartUpload ------ �쳣�����ֿ��ϴ�
	listMultipartUploads ------ �г����ڽ��еķֿ��ϴ�����
	multiuploadFile ------ ʹ�÷ֿ��ϴ�һ�����ļ�
(4)ǩ��URL����
	signUrl ------ ����ǩ��url
