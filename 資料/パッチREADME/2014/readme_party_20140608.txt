eramaou_party_20140608

��(eramaou�@ver.0.302�𐄏�)

���M�E���ρE�ăA�b�v���[�h�͂����R�ɂǂ����B

���g����
�@�S�Ă�ERB�t�@�C����ERB�t�H���_�ɏ㏑���R�s�[���Ă��������B

���d�l
�@�E�_���W�����ŗE�ҒB���p�[�e�B��g�񂾎��Ƀ��b�Z�[�W��\�����܂��B
�@�E���C�����j���[�̔\�͂̕\���������Ƃ��ɗE�ҒB�̃p�[�e�B�̑g�ݍ��킹��������܂��B
�@�@�EPL���p�[�e�B���[�_�[�APM���p�[�e�B�����o�[�A�����������Ȃ瓯���p�[�e�B�ł��B

���ǉ��E�C���ӏ�
�@��DUNGEON_PARTY.ERB
�@123�s�ڂ�147�s�ڂɈȉ��̕���}��
�@IF CHARID == NEW
�@		PRINTFORMW %SAVESTR:CHARID%�̓p�[�e�B�̃��[�_�[�ɂȂ����I
�@ELSE
�@		PRINTFORMW %SAVESTR:NEW%��%SAVESTR:CHARID%�̃p�[�e�B�ɉ�������I
�@ENDIF
�@
�@��CHARA_INFO.ERB
�@75�s�ڂ̗̑́E�C�̓o�[��8�����ɒZ�k
�@PRINTFORM  HP%BARSTR(BASE:COUNT:0,MAXBASE:COUNT:0,8)% �C%BARSTR(BASE:COUNT:1,MAXBASE:COUNT:1,8)%
�@90�s�ڂɈȉ��̕���}���B
	;�p�[�e�B�t���O
	;�p�[�e�B�����o�[
	IF CFLAG:COUNT:533 > 0 && CFLAG:COUNT:531 == 0 && CFLAG:COUNT:532 == 0 && CFLAG:COUNT:533 != COUNT
		SETCOLOR 255,100,100
		PRINTFORM  PM<{CFLAG:COUNT:533}>
		RESETCOLOR
	;�p�[�e�B���[�_�[
	ELSEIF CFLAG:COUNT:533 > 0
		SETCOLOR 255,100,100
		PRINTFORM  PL<{CFLAG:COUNT:533}>
		RESETCOLOR
	ENDIF

�@
�@
