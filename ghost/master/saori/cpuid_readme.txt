#######################################################
SAORI	CPU/OS���擾�v���O�C��	saori_cpuid.dll

	Copyright 2002 Ewi Nanase (nanase@himawari-c.com)
#######################################################

######################################################
#		�T�v
######################################################
saori_cpuid.dll��CPU/OS�̏����擾����SAORI���W���[���ł��B


######################################################
#		�g�p���@
######################################################
���L�̃p�����[�^��n���Ă��ƁA����ɂ��Ă̏���
�Ԃ��Ă��܂��B

����ł̎g�p��
{$os_name={$saori("saori_cpuid.dll","os.name")}}
�ɂ�{$os_name}�ɃI�y���[�e�B���O�V�X�e���̖��̂��������܂��B


######################################################
#		����
#
######################################################
#		�I�y���[�e�B���O�V�X�e���֘A
#
os.name		�I�y���[�e�B���O�V�X�e���̖���
			��: Windows XP Home Edition
				Windows 98

os.version	�I�y���[�e�B���O�V�X�e���̃o�[�W�����ԍ�
			��FWindows XP = 5.1
				Windows 2000 = 5.0
				Windows Me = 4.90
				Windows 98=  4.10

os.build	�I�y���[�e�B���O�V�X�e���̃r���h�ԍ�


#####################################################
#		�b�o�t�֘A���
#

cpu.num		�b�o�t�̌�

cpu.vender	�b�o�t�̃x���_�[��
			��:GenuineIntel

cpu.name	�b�o�t�̖���
			���K�������ڂ������̂��o��Ƃ͌���Ȃ��B

cpu.ptype		�b�o�t�v���Z�b�T�[�^�C�v�R�[�h

cpu.family		�b�o�t�t�@�~���R�[�h

cpu.model		�b�o�t���f���R�[�h

cpu.stepping	�b�o�t�X�e�b�s���O�R�[�h

cpu.mmx		MMX�@�\�̗L��
			�L��: Ready
			����: Not Ready

cpu.sse		SSE�@�\�̗L��
			�L��: Ready
			����: Not Ready

cpu.sse2	SSE2�@�\�̗L��
			�L��: Ready
			����: Not Ready

cpu.tdn		3DNow!�@�\�̗L��
			�L��: Ready
			����: Not Ready

cpu.mmx+	MMX+�@�\�̗L��
			�L��: Ready
			����: Not Ready

cpu.tdn+	3DNow!+�@�\�̗L��
			�L��: Ready
			����: Not Ready

cpu.clock	�b�o�t�̃N���b�N�X�s�[�h
			MH�P�ʂŎ擾

cpu.clockex	�b�o�t�̃N���b�N�X�s�[�h
			MH�P�ʂŎ擾�i�����_�R���܂Łj


#####################################################
#		�������֘A���
#

mem.os		�������̎g�p��

mem.phyt	���������� �S��(MB) 

mem.phya	���������� ��(MB)

mem.pagt	�y�[�W�t�@�C���T�C�Y �S��(MB)

mem.paga	�y�[�W�t�@�C���T�C�Y ��(MB) 

mem.virt	���z������ �S��(MB) 

mem.vira	���z������ ��(MB) 


#####################################################
#		���̑�
#
platform	�v���b�g�t�H�[������
			����: materia.exe,embryo.exe��
			SSP:  ssp.exe
			�����݂����ȉ���: duet.exe


#####################################################

<< ���ϗ��� >>
Version 1.0.4	2002/04/01	"cpu.clock"�A"cpu.clockex"��CPU�̃N���b�N�X�s�[�h
							���擾�ł���悤�ɂ��܂����B

Version 1.0.3	2002/03/31	cpu.famiry ���@cpu.family�ɏC���i�X�y���~�X�j
							cpu.stepping���擾�ł��Ȃ��s����C��
							�h�L�������g��cpu.pname�Ƃ��邪���ۂɂ�cpu.ptype�i�h�L�������g�̏C���j

Version 1.0.2	2002/03/31	"platform"�̒ǉ��B
							�f�o�b�O��saori.txt���o�͂��Ă����s����C���B

Version 1.0.1	2002/03/30  Pentium�ȊO��CPU��CPU���̂̕s����C�����܂����B

Version 1.0.0	2002/03/30	�t�@�[�X�g�����[�X



#####################################################
<<�A����>>
�������[���� (nanase@himawari-c.com)
http://www.himawari-c.com/

