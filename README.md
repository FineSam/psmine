# PSmine (PowerShell for Redmine )
Powershell��Redmine�𑀍삷�邽�߂̃X�N���v�g�ł��B�ȉ��̍�Ƃ�Powershell�v�����v�g������{�ł���悤�ɂȂ�܂��B  
- �`�P�b�g�ꗗ�̕\��  
- �`�P�b�g�̏ڍו\��  
- �`�P�b�g�̓o�^  
- �`�P�b�g�̍X�V�i�����X�V�j  
- �`�P�b�g�̍X�V�i�X�e�[�^�X�ύX�j     

##�g����
###�`�P�b�g�ꗗ���m�F����
psmine.ps1 show �R�}���h���g���܂��B
	> .\psmine.ps1 show
	
	
	ID      : 50
	project : tech
	subject : kibana3 elasticseach�����o�v���o�R�ɂ���B
	status  : �V�K

	ID      : 49
	project : tech
	subject : kibana3 �_�b�V���{�[�h�ɕ\�������f�[�^���@�킲�ƂɌ��肷��B
	status  : �V�K

###����̃`�P�b�g�̏ڍׂ��m�F����B
psmine.ps1 show id {number}�@���R�}���h���g���܂��B
	> .\psmine.ps1 show id 44
	>> Ticket Summary

	ID      : 44
	PROJECT : home
	STATUS  : �I��
	TITLE   : �ł̂��g��
	
	
	
	>> Ticket Detail
	
	
	created_on                                                       name                                                     notes                                                          
	----------                                                       ----                                                     -----                                                          
	2014-03-10T15:36:19Z                                             kongou-ae                                                ���܂�������                                                         
	2014-03-11T07:51:29Z                                             kongou-ae                                                ����[�ނ��ۂ����܃h���b�V���O������                                             
	2014-03-11T07:59:28Z                                             kongou-ae                                                ���_�Ђ�                                                           
	2014-03-13T06:34:17Z                                             kongou-ae                                                             
###�`�P�b�g�̗������X�V����
psmine.ps1 update id {number} {note}�@���R�}���h���g���܂��B
	> .\psmine.ps1 update id 45 �x���_�[�ւ̖₢���킹�����{�����B
	�X�V���������܂���

###�`�P�b�g�̃X�e�[�^�X���X�V����B
psmine.ps1 change id {number} {open|start|close}�@���R�}���h���g���܂��B
	> .\psmine.ps1 change id 45 close
	�X�V���������܂���

## ���O����
1. config.xml.sample���Q�ɂ��āAconfig.xml���쐬���܂��B���[�UID�́ARedmine�̉�ʉE��ɕ\������Ă���A�J�E���g���̃����N��URL�̖����ɋL�ڂ���Ă��鐔���ł��BrmId�͎��̃X�e�b�v�Ŋm�F���܂��B  
2. psmine.ps1 show�����s���Ă��g����Redmine�ɂ�����X�e�[�^�XID���m�F���܂��B�\�����ʂ���A���g���̊���open/start/close�Ƀ}�b�`����ID�i�����j��config.xml�ɓ��͂��Ă��������B  
