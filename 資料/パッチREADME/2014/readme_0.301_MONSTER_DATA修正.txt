eramaou0.301_MONSTER_DATA�C��

�O�����
eramaou0.301 + eramaou_PREGNANCY_20140526

�C���_
CHARA_MARRIAGE.ERB	CALL MONSTER_DATA �� CALL MONSTER_DATA, GROOM_NUM, 5 �ɏC��
DUNGEON_BATTLE.ERB	CALL MONSTER_DATA �� CALL MONSTER_DATA, X, COUNT, A, -1 �ɏC��
			@SPEED_PLUS�����������ƏC��
			@MONSTER_LIST��������ƏC��
DUNGEON_BATTLE2.ERB	CALL MONSTER_DATA �� CALL MONSTER_DATA, CFLAG:A:570, 3, A, -1 �� CALL MONSTER_DATA, CFLAG:T:570, 4, -1, B �ɏC��
INVASION.ERB		CALL MONSTER_DATA �� CALL MONSTER_DATA, X, 0 �ɏC��
INVASION_RYOUZYOKU.ERB	@INVASION_RYOUZYOKU��������ƏC��
MARRIAGE_DAY.ERB	CALL MONSTER_DATA �� CALL MONSTER_DATA, LOCAL:0, 5 �ɏC��
MONSTER_DATA.ERB	�ϐ�E�ȊO�̈ꕶ���ϐ���u������
			�s�N�V�[�E�f�����n���E���@���p�C�A�̑ϐ��������ɂȂ��Ă����̂ŏC��
			�_�C�XLOCAL:1(���͕ϐ�Z)�̋������������������̂ŏ�����ǉ�
			(���̕ύX�Ŏ��X�{�X�����N����悤�ɂȂ������Ǒ��v���낤��)
MONSTER_PLAY.ERB	CALL MONSTER_DATA �� CALL MONSTER_DATA, LOCAL:0, 5 �ɏC��

�C�ɂȂ����_
DUNGEON_BATLLE.ERB�ɂ��� ;�S�Ŏ� IF B >= 400
�͎��s����Ȃ��悤�Ɍ����邯�ǕK�v�Ȃ̂�

