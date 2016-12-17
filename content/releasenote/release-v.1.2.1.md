---
date: "2016-12-17"
title: "�����[�X v1.2.1"
slug: "v.1.2.1" 
author: "Rancher JP"
description: "�����[�X v1.2.1"
draft: false
tags:
  - "releasenote"
categories:
  - "releasenote"
archives:
  - 2016
  - 2016/12
---

## �o�[�W����
* rancher/server:v1.2.1
* rancher/agent:v1.1.1
* rancher/lb-service-haproxy:v0.4.6
* [rancher-compose-v0.12.1](https://github.com/rancher/rancher-compose/releases/tag/v0.12.1)
* [rancher-v0.4.1](https://github.com/rancher/cli/releases/tag/v0.4.1)

> *����:* �V����[infrastructure services](http://docs.rancher.com/rancher/v1.2/en/rancher-services/)�ł́A���[�h�o�����T�̋@�\���w���HAProxy�C���[�W�ɕύX���A�l�b�g���[�N�G�[�W�F���g���N������Ȃ��Ȃ�܂����B ���������āArancher/agent-instance���K�v�Ȃ��Ȃ�܂����B

## Rancher �T�[�o�[��v1.1.4����A�b�v�O���[�h
�K���f�[�^�x�[�X���o�b�N�A�b�v���Ă��������BRancher 1.2.0�փo�[�W�����A�b�v��ɂ́A�ȑO�̃o�[�W�����ɖ߂����Ƃ͂ł��܂���B�߂������ꍇ�́A�ȑO�����Ă����o�[�W�������_�ł̃f�[�^�x�[�X�̃X�i�b�v�V���b�g�𗘗p���邵������܂���B�f�[�^�x�[�X�̃o�b�N�A�b�v������Ă���A�h�L�������g�ɏ]���ăA�b�v�O���[�h���J�n���Ă��������B

> **����:** AWS �Z�L�����e�B�O���[�v�𗘗p���Ă���ꍇ�A�K��ICMP���Z�L�����e�B�O���[�v�ŗL���ɂ��Ă��������B

## ���̃A�b�v�O���[�h
Rancher�T�[�o�[���A�b�v�O���[�h������́A1.2���ɐ���ɃA�b�v�O���[�h����܂ŁA���ɃA�N�Z�X�ł��Ȃ��Ȃ�܂��B1.2�Ńl�b�g���[�N��LB�̕ύX�����ׁA�V�����l�b�g���[�N�R���|�[�l���g�ɍX�V����Ĉڍs�����܂ŃA�b�v�O���[�h�������Ƀl�b�g���[�N���ؒf����܂��B�A�b�v�f�[�g���K�v�Ȋ����Ƃ�**Upgrade Now***��ʂ�\�����āA���X�V���邩�����߂邱�Ƃ��ł���֗��ȋ@�\��񋟂��܂����B�X�V�����s����܂ŁA�R���e�i�͋@�\�������܂����A�Ǘ��@�\�͋�����܂���B���̎��A�R���e�i�̍č쐬�i�w���X�`�F�b�N�j�ɂ���Ă����̃R���e�i�������Ȃ��Ȃ�\��������܂��BHA�ADNS�v���O���~���O�A�w���X�`�F�b�N�ȂǁARancher�̊֗^���K�v�ȋ@�\�́A��������܂Ő���ɓ��삵�Ȃ��\�������邽�߁A�����Ȃ�ׂ������A�b�v�O���[�h���邱�Ƃ����������߂��܂��B

"�������A�b�v�O���[�h"���N���b�N����ƁARancher�͊��̃A�b�v�O���[�h���J�n���܂��B���g�p�̊��̋K�͂ɂ���Ă͍ő�10�`20��������ꍇ������܂��̂ŁA���΂炭���҂����������B**Stacks** - > **Infrastructure**�̉��ɂ��邷�ׂẴX�^�b�N��**active**��ԂɂȂ��Ă�����A���͐���ɍX�V����Ă��܂��B

*__Kubernetes���̕��́A���ׂẴC���t���X�g���N�`���T�[�r�X���u�A�N�e�B�u�v��ԂɂȂ�����A������k8s v1.2.6�X�^�b�N��v1.4.6�ɃA�b�v�O���[�h���Ȃ���΂Ȃ�܂���B����:k8s���A�b�v�O���[�h����ہA�����̃|�b�h���폜���čč쐬����\���̂�����m�̖�肪���邱�Ƃɒ��ӂ��Ă��������B�|�b�h�����v���P�[�V�����R���g���[���̈ꕔ�łȂ��ꍇ�́A�č쐬����܂���B ����ɍl�����Čv�悵�Ă��������B���̃P�[�X�ł��A�b�v�O���[�h�v���Z�X�͊��ɉ�����5�`10���ȏォ����ꍇ������A�X�^�b�N���A�N�e�B�u�ȏ�ԂɂȂ�Ɗ������܂��B__*

### �A�b�v�O���[�h�̊��m�̐�������
* Swarm���̃A�b�v�O���[�h�̓T�|�[�g����Ă��܂���BDocker��Docker�G���W���Ɉڍs���邱�ƂɊւ���Docker Swarm����̕ύX�ɂ��ASwarm�̃T�|�[�g���ŐV��Docker 1.12 Swarm����ɂȂ����ׂł��B 
* ���e���v���[�g�I�v�V������\������}�C�O���[�V�����p�t�H���_�̃J�^���O�G���g��������������܂��B �����̃J�^���O�E�G���g���[�́A�Â��G���g���[�ւ̃��[���o�b�N���T�|�[�g���Ă��܂���B �Ⴆ�΁AKubernetes�ɂ��ׂĂ̊O��DNS�G���g�����܂܂ꂱ��ȊO�ɂ����l�̂��̂�����܂��B 
* v1���[�h�o�����T����v2���[�h�o�����T�ւ̃A�b�v�O���[�h���ɁA�Z���N�^���g�p���郋�[���̓A�b�v�O���[�h����܂���B �����̃��[���́A���̃A�b�v�O���[�h��Ƀ��[�h�o�����T�[�ɍēx�ǉ�����K�v������܂��B
* 1.2����́ARancher��cadvisor����̓��v�����擾�����ADocker�̓��v��񂩂�擾���܂��B ����ɂ��APrometheus�̂悤��cadvisor�Ɉˑ���������̃J�^���O�́ADocker�̓��v��񂩂�擾����悤�ɏC�������܂ŋ@�\���Ȃ��Ȃ邱�Ƃɒ��ӂ��Ă��������B

## v1.2.0����̎�ȃo�O�C��

* boot2docker �z�X�g�� rancher/plugin-manager:v0.2.12�ɂ����������C���A�V���� rancher/network-manager:v0.2.13 �l�b�g���[�N�T�[�r�X������܂��B�l�b�g���[�N�T�[�r�X�X�^�b�N��"�A�b�v�O���[�h���p�\" ���{�^���\������Ă���ꍇ�́A�A�b�v�O���[�h���Ă��������B[#6874]
* Fixed an issue where docker doesn't have to be installed at var/lib/docker in order for networking to work. [#6897]
* docker ��
* ipsec ��vxlan �������̓C���t���X�g���N�`���[�̃l�b�g���[�N�T�[�r�X�Ńf�t�H���g��docker0 ����docker �u���b�W���\���ł���悤�ɏC�����܂����B[#6896]
* UI���ł܂��Ă��܂������C�� [#6995]
* Rancher���f�[�^�x�[�X��K�؂ɃN���[�j���O���Ă��炸�ARancher UI�����b�N�A�b�v���Ă��Ȃ��̂��C�� [#6826, #6978, #6985 ]
* Rancher�h���C���𗘗p����O��Rancher�T�[�r�X���o���z�X�g�̃p�X���������邱�Ƃ��ł��Ȃ������̂��C�� [#7010]
* ���[�h�o�����T�[���z�X�g�����g���ĊO���T�[�r�X���^�[�Q�b�g�ɂł��Ȃ��̂��C�� [#2624]
* ��~���̃R���e�i�̃��O��������C�� [#6442]
* HA�\���Ńm�[�h�����邱�Ƃ��ł��Ȃ��̂��C�� [#6814]
* �����T�[�r�X�����^�[�Q�b�g�Ƃ��郍�[�h�o�����T�[����X�^�b�N���ŃG�N�X�|�[�g���C�� [#6829]
* UI��Ń��[�h�o�����T�[�Ƀz�X�g��IP�A�h���X���w�肷�邱�Ƃ��ł��Ȃ��̂��C�� [#6852]
* �R���e�i���������g�̃z�X�g����ping�ł��Ȃ��̂��C�� [#6855]
* �Â��l�b�g���[�N�G�[�W�F���g�Ɋ֘A���Ă���e�[�u���ɂ��CPU�g�p���������Ȃ�̂��C�� [#6857]
* Rancher-commpose �Ń��[�h�o�����T�[��������Rancher�ō쐬����Ȃ������C��
* haproxy�̃J�X�^���ݒ肪�\�[�g����Ȃ��̂��C�� [#6888]
* GCR(Google Container Registry)����docker�C���[�W���v�����邱�Ƃ��ł��Ȃ��̂��C�� [#6916]
* �A�b�v�O���[�h��Ƀ��[�h�o�����T�[��haproxy�ݒ肪�\������Ȃ������C�� [#6921]
* volumes ���L�[�Ƃ����ϐ��� compose v2�t�@�C���Œu������Ȃ������C�� [#6936]* �z�X�g�o�^URL��http���󂯕t���Ȃ��Ƃ��������C�� [#6957]
* Rancher�G�[�W�F���g��proxy�Ɋւ�����ϐ����啶���Ə���������ʂ��������C��  [#7019]
* ���[�h�o�����T�[�̃��O�������悭����������C��