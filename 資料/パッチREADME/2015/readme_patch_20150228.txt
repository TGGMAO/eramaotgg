eramaou_patch_20150228

��(eramaou�@ver.0.340����)

���M�E���ρE�ăA�b�v���[�h�͂����R�ɂǂ����B

���g����
�@�S�Ă�ERB�t�@�C����ERB�t�H���_�ɏ㏑���R�s�[���Ă��������B

���d�l
�E�������Ă������x�������Ȃ��ƍč��o���Ȃ��悤�ɂ��܂����B
�E�o�O�C���B�A�C�e���Ƃ̌������o���Ȃ��悤�ɂ��܂����B
�E�o�O�C���BRAND:0�ɂȂ�Ȃ��悤��@NAKADASHI_CHECK�֐����C�����܂����B
�E�o�O�C���B���Ȃ��Ɠz�ꂪ�����������ɏ]�����R�ȏ�Ȃ���Ύ~�܂�o�O���C�����܂����B

���ǉ��E�C���ӏ�
�@��CHARA_MARRIAGE.ERB
�@�@�����X�^�[�ȊO�̃A�C�e����r�����邽�߂�
�@�@83�s�ڂɈȉ��̕����ǉ��B
�@�@ELSEIF RESULT <= 99
		PRINTL ����̓A�C�e���ł�
		GOTO INPUT_LOOP
	89�s�ڂɈȉ��̕����ǉ��B
	ELSEIF CFLAG:ARG:601 > 0
		PRINTFORMW %SAVESTR:ARG%�͂��łɌ������Ă���
	RETURN 0

�@��EVENT_PREGNANCY.ERB
�@�@�ǐ����グ�邽�߂�@NAKADASHI_CHECK�֐��Ɉȉ���#DIM��ݒ肵��LOCAL:0��LOCAL:1��u���B
	#DIM NAKADASHI_PARTNER
	#DIM HAIRANZAI
�@�@236�s�ڈȍ~���ȉ��ɏC��
�@�@;�l�T�̏ꍇ�A�������ɔD�P���₷��
�@�@IF TALENT:(ARG:0):314 == 2 && DAY:2 >= 14 && DAY:2 <= 16 && CFLAG:(ARG:0):109 == 1
		HAIRANZAI = 1
�@�@ELSEIF TALENT:(ARG:0):314 == 2 && DAY:2 >= 14 && DAY:2 <= 16
		HAIRANZAI = 2
�@�@ENDIF

�@��MARRIAGE_DAY.ERB
�@�@�P�A���X�~�X���������̂ŏC���B
�@�@200�s�ڂ��ȉ��ɏC��
�@�@PRINTFORML %SAVESTR:A%�͂��Ȃ��ƕ�炵�Ă���B
�@�@221�s�ڂ��ȉ��ɏC��
�@�@ELSEIF MARK:A:3 >= 1

�@
