eramaou_�t�B���^_������_20131009

��(eramaou�@ver.0.270����)

���M�E���ρE�ăA�b�v���[�h�͂����R�ɂǂ����B

���g����
�@eramaou_0.270�p�b�`�܂Ƃ�20131005.zip��K�p���Ă���
�@�S�Ă�ERB�t�@�C�����㏑�����Ă��g����������

���d�l
�E���C�����j���[�ŁuAssistant�v��I��ŏ����I������Ƃ��Ɂu����𖳂��v��I�ׂ�悤�ɂ��܂����B
�E�����J�n���ɏ��肪���Ȃ��ꍇ�u����͖����v�u�i���C�����j���[�Ɂj�߂�v��I�ׂ�悤�ɂ��܂����B
�E������/�R���t�B�O�ň����n�A���n�A�`�����n�A�u�����n�ASM�n�R�}���h���t�B���^�����O�\�ɂ��܂����B
�E�������ŐE�Ɩ��ł͂Ȃ����O���\�������悤�ɂ��܂����B
�E�E�҂����x���A�b�v����Ƃ��ɂ܂Ƃ߂ă��x���A�b�v����悤�ɏC���B

2013/10/09
��USERCOM.ERB
@SHOW_USERCOM�֐���
FLAG:25 & 1 �����n�t�B���^
FLAG:25 & 2 ���n�t�B���^
FLAG:25 & 4 �`�����n�t�B���^
FLAG:25 & 8 �u�����n�t�B���^ 
FLAG:25 & 16 �r�l�n�t�B���^
��ǉ��B

��COMABLE.ERB
�e��R�}���h�Ƀt�B���^�̃`�F�b�N��ǉ�
�t�B���^����Ă�����RETURN 0��Ԃ��悤�ɂ��܂��B

��SHOP.ERB
80�s�ڂɈȉ���ǉ�
SIF RESULT == 2
	RETURN 0

272�`273�s�ڂ��ȉ��ɏC��
PRINTL [100] ����͖���
PRINTL [101] �߂�

280�s�ڂ��ȉ��ɏC��
ELSEIF RESULT >= A && RESULT != 100 && RESULT != 101

284�`290�s�ڂ��ȉ��ɏC��
IF RESULT == 100
	ASSI = -1
	RETURN 0
ENDIF

SIF RESULT == 101
	RETURN 2

@CONFIG�֐��ɒ������t�B���^��ǉ�
FLAG:5�̃t���O�Ǘ����r�b�g���Z��

��SHOP_LABO.ERB
%NAME:*%�ƂȂ��Ă����Ƃ����%SAVESTR:*%�ɒu��

��LVUP.ERB
9�`18�s�ڂ�$LVUP_REPEAT���x����ǉ�

