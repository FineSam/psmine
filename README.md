# redmine_cli
�p���[�V�F����Redmine�𑀍삷�邽�߂̃X�N���v�g�ł��B�ȉ��̍�Ƃ�Powershell�v�����v�g������{�ł���悤�ɂȂ�܂��B  
- �`�P�b�g�ꗗ�̕\��  
- �`�P�b�g�̏ڍו\��  
- �`�P�b�g�̓o�^  
- �`�P�b�g�̍X�V�i�����X�V�j  
- �`�P�b�g�̍X�V�i�X�e�[�^�X�ύX�j     



##�g����
###�`�P�b�g�ꗗ���m�F����
	rm_cli.ps1 show

###����̃`�P�b�g�̏ڍׂ��m�F����B
	rm_cli.ps1 show id {number}  
###�`�P�b�g�̗������X�V����
	rm_cli.ps1 update id {number} {note}

###�`�P�b�g�̃X�e�[�^�X���X�V����B
	rm_cli.ps1 update id {number} {open|start|close}



## ���O����
1. config.xml.sample���Q�ɂ��āAconfig.xml���쐬���܂��B���[�UID�́ARedmine�̉�ʉE��ɕ\������Ă���A�J�E���g���̃����N��URL�̖����ɋL�ڂ���Ă��鐔���ł��BrmId�͎��̃X�e�b�v�Ŋm�F���܂��B  
2. rm_cli.ps1 show�����s���Ă��g����Redmine�ɂ�����X�e�[�^�XID���m�F���܂��B�\�����ʂ���A���g���̊���open/start/close�Ƀ}�b�`����ID�i�����j��config.xml�ɓ��͂��Ă��������B  
