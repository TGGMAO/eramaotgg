eramaou_DRAW_MAINMENU_SHOP_��������ver2 20131012

��(eramaou�@ver.0.270����)

���M�E���ρE�ăA�b�v���[�h�͂����R�ɂǂ����B

���g����
�@eramaou_0.270�p�b�`�܂Ƃ�20131005.zip��eramaou_�N��_�t�B���^_������.zip��K�p���Ă���
�@�S�Ă�ERB�t�@�C����ERB�t�H���_�ɏ㏑���R�s�[���Ă��������B

���d�l
2013/10/12
�E�E�҂����Y�����Ƃ��Ƀ��x���A�b�v���₷�����܂����B
�E���C�����j���[����TARGET�����AASSISTANT�L�莞�̕\�L����
�E�̗͉񕜂̎d�l���������������̂ŏC���i�ߌ�̒�����̗͉̑񕜂��傫���Ȃ�悤�Ɂj
�E���Y��ɏ���ɏo���Ȃ��L����������ɂȂ������������B
�E�L�������p��ɏ���ɏo���Ȃ��L����������ɂȂ������������B
�E@EVENTTURNEND�̍Ō�ɑO��̒����ΏۂƑO��̏����TARGET��ASSI�ɖ߂�悤�ɒǉ��B
�@���̍�Ƃ̓I�[�g�Z�[�u����@SAVEINFO�ł���Ă������߁B����ŃI�[�g�Z�[�u�@�\�������ł���肪�����Ȃ�悤�ɁB

��SYSTEM.ERB
208�s�ڂ��C����IF TIME == 1

547�s�ځ`549�s�ڂɁu�O��̒����ΏۂƑO��̏����߂��v��ǉ�

��SELL_CHARA.ERB
@KILL_TARGET�֐����̏���̏��̎擾�Ə����߂����폜

��EXECUTION.ERB
167�`177�s�ڂ�FLAG:1��FLAG:2����or���Z���閽�߂�ǉ�
���l�̂��̂�@EXECUTION_MINI�֐����ɒǉ�

191�E232�s�ڂ��C����IF FLAG:80 >= CFLAG:0:9

��_DRAW_MAINMENU.ERB
99�`101�s�ڂ�
sif target < 0
PRINTFORM %"",36%
sif target > 0
��ǉ��B

2013/10/11
�E_DRAW_MAINMENU.ERB��SHOP.ERB�̃o�O�΍���C��
�E���C�����j���[�ŏ���͖�����I�񂾎��ɈȑO�̏���ɖ߂�Ȃ��悤�ɏC��
�E��������`�F�b�N���C��

��EVENT_NEXTDAY.ERB
98�`110�s�ڂ܂ŏ�������`�F�b�N�ɕύX�B
OFFERVIRGIN_CHECK�֐��̃`�F�b�N��
���������ɂ��Ȃ��ƃ_��
�O��̒����ΏۂƓ�������Ȃ��ƃ_��
��ǉ�

��_DRAW_MAINMENU.ERB
8�s�ڂ�ύX��SIF TARGET > CHARANUM - 1

12�s�ڂ�ύX��SIF ASSI > CHARANUM - 1

��SHOP.ERB
7�s�ڂ�ύX��SIF TARGET > CHARANUM - 1

11�s�ڂ�ύX��SIF ASSI > CHARANUM - 1

286�s�ڂɒǉ���FLAG:2 = ASSI


2013/09/29
�E�呀�т̃J�M���̂Ă��悤�ɂ��܂����B
�@��
�E�呀�т̃J�M���̂Ă�ꂽ�q�́u�}���v�Ń_���W������T�����ɒ呀�т̃J�M��T���܂��B
�@��
�E�呀�т̃J�M���������q�͂�������҂��ď��������サ�ɗ��܂��B

SHOP_TAILOR.ERB
99�s�ڂ̒呀�т̃J�M���̂Ă�����ɍĐ��������s��ǉ��B
798�s�ڂ̕��͂��C���B

DUNGEON.ERB
251�s�ڈȍ~�ɒ呀�т̃J�M��T�������ǉ�
1/64�ŃJ�M�𔭌����܂��B�i���Ɖ������H�j

EVENT_NEXTDAY.ERB
98�s�ڈȍ~�̃R�����g�A�E�g���폜����OFFERVIRGIN_CHECK�֐��ɔ�ׂ�悤��
OFFERVIRGIN_CHECK�֐��̃`�F�b�N��
�呀�т̌����̂ĂĂȂ��ƃ_��
�呀�т̌��������ĂȂ��ƃ_��
��ǉ����Ē呀�ъ֌W�ł���������������Ȃ��悤�ɂ��܂����B


