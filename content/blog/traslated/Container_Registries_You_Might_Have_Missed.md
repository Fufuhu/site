---
date: "2016-12-22"
title: "[�|��]��������Ă��邩������Ȃ��R���e�i�̃��W�X�g��"
slug: "container-registries-might-missed-ja" 
author: ""
description: "�l�X�ȃR���e�i���W�X�g���ɂ��ĊT�v�̖|��"
draft: true
tags:
  - "blog"
categories:
  - "blog"
archives:
  - 2016
  - 2016/12
---
�ȉ��́A
Rancher Labs | Container registries you may have missed | Rancher Labs
http://rancher.com/container-registries-might-missed/
����̖|��ł��B

Container Registries You Might Have Missed
��������Ă��邩������Ȃ��R���e�i�̃��W�X�g��

2016�N11��10�� [Vince Power](http://rancher.com/author/vince-power/)

���W�X�g���́A�R���e�i��������ŏd�v�ȃR���|�[�l���g�̈�ŁA����Docker�ł͑����̐l���璍�ڂ𗁂тĂ��܂��B���W�X�g���́A�R���e�i�G���W���z�X�g�Ƀ_�E�����[�h���s�����C���[�W��ۊǂ��܂��B�R���e�i�͂��̓���̃C���[�W�̒P�Ȃ�C���X�^���X�ł��B�C���[�W�́AMicrosoft Windows��MSI��Red Hat Enterprise Linux��RPM�ȂǁA�����Ɏg����p�b�P�[�W�̂悤�Ȃ��̂ƍl���邱�Ƃ��ł��܂��B���W�X�g���́A�ǂ��������ɓ��삷�邩�ڍׂɂ͏q�ׂ܂��񂪁A�ڍׂ�m�肽���ꍇ�͂��̋L��[�f���炵���L��](http://rancher.com/comparing-four-hosted-docker-registries/)��ǂނƗǂ��ł��傤�B

���̋L���Ő������������Ƃ͎��̒��ڂ��Ă��郌�W�X�g���̂����������グ�Ă݂����Ǝv���܂��BDocker���g���l�ɂƂ��Ă͗L���ȃ��W�X�g���͊��ɒm���Ă���Ǝv���܂����A�ǂ��ɃC���[�W��u���������߂�̂ɍl�����鉿�l�̂��鏬�K�͂ȃ��W�X�g��������܂��B

���܂�m���Ă��Ȃ������̃R���e�i���W�X�g���ɂ��Ă��������Ă݂܂��傤�B

# �悭�m���Ă��郌�W�X�g��

�܂��A���ɑ����郌�W�X�g�������X�g�A�b�v���܂��B���̏�Œ��ڂ��Ă��郌�W�X�g���Ɣ�r���܂��傤�B

���݁A�S�Ă�Docker���[�U�[����ł��l�C�̂��郌�W�X�g����[Docker Hub](https://hub.docker.com/)�ł��BDocker Hub�̓��W�X�g���E�̒��S�ł��B�S�Ă�Docker���f�t�H���g�Ń��W�X�g���̃z�X�g��Ƃ��ēo�^����Ă��܂��B

���̑��̐��ɍL���m���Ă��郌�W�X�g��:
* [Docker Trusted Registries](https://docs.docker.com/docker-trusted-registry/) (Docker���z�z���Ă���I�[�v���\�[�X)
* [Quay.io](https://quay.io/) (CoreOS���񋟂��Ă��郌�W�X�g��)
* [Enterprise Registry](https://tectonic.com/quay-enterprise/) (Quay�̃I���v���~�X��)
* [Google Container Registry](https://cloud.google.com/container-registry/) (GoogleCloud�v���b�g�t�H�[�����񋟂��Ă��郌�W�X�g��)
* [Artifactory](https://www.jfrog.com/artifactory/) (JFrog���񋟂��Ă���B�T�[�r�X�^��A�I���v���~�X�ɂł��郌�W�X�g��)

# ���܂�m���Ă��Ȃ��R���e�i���W�X�g��

���āA���ڂ̃p�[�g�ł��B��������͂��܂�m���Ă��Ȃ����W�X�g�����T�����܂��B

## Amazon EC2 �R���e�i���W�X�g�� (ECR)

Amazon��[Amazon EC2�R���e�i�[�T�[�r�X(ECS)](https://aws.amazon.com/ecr/)�ƌĂ΂��R���e�i�T�[�r�X��񋟂��Ă��邱�Ƃ͂��łɂ��������Ǝv���܂��B�������AECS�̊������S�ɐ����郌�W�X�g���ɂ��Ă͂��܂�m���Ă��܂���B

Amazon EC2 �R���e�i���W�X�g��(ECR)�ƌĂ΂�邱�̃��W�X�g���́ADocker�̃R���e�i���W�X�g���Ƃ��Ē񋟂���Ă��܂��BECS�Ɠ�������Ă��܂��B2015�N12���ɓ������ꂽ����́A���̑��̂悭�m���Ă��郌�W�X�g���ɔ�ׂĂ��܂肵���Ă��܂��񂪁A���̗��R��������܂��傤�B

ECS�́AECR�Ƃ̂݌݊���������R���e�i���W�X�g���ł͂���܂���BECS�͊O���̃��W�X�g���Ƃ��Ă��g�����Ƃ��ł��܂��B�������AECR�̏d�v�ȓ_�͊��S�ɃT�[�r�X�Ƃ��ĊǗ����ꂽ���W�X�g���ŁA�W�J�ƊǗ����V���v���ɂ��Ă��܂��BECR�́AECS�̃C���t���Ɠ����悤�Ɋg����������A�X�P�[���u���ł���Ƃ������Ƃł��B

__�x�X�g�ȃ��[�X�P�[�X:__ AWS�̃w�r�[���[�U�[�Ńv���C�x�[�g�ȃC���[�W��ۊǂ���ꏊ���������Ă���̂Ȃ�΁AECR���g���͔̂��ɍ����I�ł��B��K�͂Ƀ��W�X�g����W�J����ꍇ��A�����I�Ƀ��W�X�g�����g�傷�邱�Ƃ��z�肳���ꍇ�ɂ��K���Ă��܂��B�����̏ꍇ�AECR�̎����㖳�����̊g�����̃����b�g������ł���ł��傤�B

## FlawCheck �v���C�x�[�g���W�X�g��

[FlawCheck�v���C�x�[�g���W�X�g��](https://www.flawcheck.com/) (�ŋ߁A�Z�L�����e�B�x���_�[Tenable�Ђɂ���āAFlawCheck�̃r�W�l�X�̎c��̕����ƈꏏ�ɁA��������܂���)�Z�L�����e�B�d���̃��W�X�g���ł��B�R���e�i�̃C���[�W�ɑ΂���Ǝ㐫�X�L�����ƃ}���E�F�A���o���g�ݍ��܂�Ă��āA�T�[�r�X�Ƃ��Ē񋟂���Ă��܂��B�����̃R���e�i�C���[�W�ɑ΂��鈫�ӂ̂���R�[�h�̖��ߍ��݂∫�ӂ̂���C���[�W�������Ă��܂�����h�����߂̓�����͂���܂��񂪁AFlawCheck�ł́A�X�L�����@�\�ɂ�肻�̃��X�N���y�����邱�Ƃ��ł��܂��B

__�x�X�g�ȃ��[�X�P�[�X:__ �Z�L�����e�B�ӎ��̍�����ƂɂƂ��ẮA����͂ƂĂ��ǂ��@�\���Ǝv���܂��B�������K�����ꂽ�ƊE�ł͗��p��������ł��傤�B

## GitLab Container ���W�X�g��

[Gitlab �R���e�i���W�X�g��](https://docs.gitlab.com/ee/user/project/container_registry.html)�́A�I���v���~�X�⃌���^���T�[�o�[�Ń��W�X�g���Ƃ��Ď��s���邱�Ƃ��ł���R���e�i�C���[�W����舵�����Ƃ��ł���GitLab�Ђ̃\�����[�V�����ł��BGitLab�ɑg�ݍ��܂�Ă���̂ŁAGitLab�̃f�v���C�̃p�C�v���C���ɒ��ړ������邱�Ƃ��ł��AGitLab�̑��̕����ƃV�[�����X�ɓ������邱�Ƃ��ł��܂��B���Ȃ��̃`�[����GitLab���g���Ă���c�[���𑝂₵�����Ȃ��ADevOps�ŃV�[�����X�ɓ������ă��[�N�t���[�𗘗p���邱�Ƃ��ł��邱�Ƃ������b�g�ł��B

__�x�X�g�ȃ��[�X�P�[�X:__ �J���҂́ADocker�C���[�W�ƃ\�[�X�R�[�h�������Ƃ��납��Q�Ƃł���ƕ֗����ƍl����ł��傤�BGitLab�Ń\�[�X�R�[�h��������悤��GitLab�R���e�i���W�X�g���Ō�����ƕ֗����Ǝv���܂��B����ŁA���̑��̃��W�X�g���\�t�g�Ɣ�ׂĂ���ƌ���������������Ă���킯�ł͂���܂���B

## Portus (SUSE��)

[Portus](http://port.us.org/)�́A�Z�p�I�ɂ̓��W�X�g���\�t�g�ł͂���܂���B�������ADocker���W�X�g���̎Г��W�J�p��UI��u����������t�����g�G���h������Ă��܂��BPortus�́A�A�N�Z�X�����̃I�v�V����������A����ɂ��Docker���W�X�g���ɒl��ǉ����邱�Ƃ��ł���悤�݌v����Ă��܂��B
����ɂ��`�[�����\��������A���W�X�g���̃��[�U�[��������A�X�̃`�[���ʂ̃A�N�Z�X������ݒ肷�邱�Ƃ��ł��܂�(�l�X�ȖʂŁA���̋@�\��Unix�̂悤�ȃV�X�e���̃��[�U�[�E�O���[�v�̎d�g�݂Ɏ��Ă��܂�)�BPortus�ł́A�X�̃��[�U�[���x���܂��́A�`�[���̃��[�U�[�ł̃R���e�i�C���[�W�̍X�V������^���邱�Ƃ��ł���l�[���X�y�[�X�����W�X�g���ɗ^���邱�Ƃ��T�|�[�g���A���܂��ȗ��x�Ń��|�W�g���ɑ΂��ĕύX���邱�Ƃ��ł��܂��B�܂��APortus�œ����I�ȓ_�́A���W�X�g���ݒ�ƃA�N�Z�X������ݒ肷�邽�߂̃��[�U�[�t�����h���[��Web�C���^�[�t�F�C�X���񋟂���邱�Ƃł��B�iCLI�\���c�[���Aportusctl�����l�ɗ��p�\�ł��B�j

__�x�X�g�ȃ��[�X�P�[�X:__ Docker���W�X�g�����D�݂����A�����ƃZ�L�����e�B�R���g���[�����K�v�Ƃ����ꍇ�A�܂��́A���悢�A�N�Z�X�������g�������Ƃ������R������ꍇ�́APortus�͋��͂ȃ\�����[�V�����ł��B

## Sonatype Nexus

[Sonatype Nexus](https://www.sonatype.com/products-sonatype)�́A�T�[�r�X�ƃI���v���~�X�ł̐ݒu���T�|�[�g����A�\�[�X�R�[�h�Ǘ��̔ėp�I�ȃ��W�X�g���ł��BDocker���W�X�g���̋@�\�ȊO�ɂ��A�����̋@�\���T�|�[�g���Ă��܂����ADocker���W�X�g�����g�����Ƃ��ł��܂��BDocker�̃��W�X�g�������Â����j��������̂Ȃ̂ŃR���e�i���W�X�g���̋@�\�Ȃ��ȑO���x�e�����̊Ǘ��҂ɂ͂��Ȃ��݂�������܂���BCore Nexus �v���b�g�t�H�[���́A�I�[�v���\�[�X�ł����A���p�̃I�v�V���������p�ł��܂��B

__�x�X�g�ȃ��[�X�P�[�X:__ �����̊�Ƃ�Nexus��Maven�̃��|�W�g���Ƃ��Ē��N���p����Ă��܂����B�P���Ɍ���I�ȃv���b�g�t�H�[���̃����[�X�ɍX�V���邾���ŁA�g�D���ŐV���Ȑ��i��^�p�X�^�b�t�̐V�����Z�p�̏K���Ȃ��ɓƎ���Docker���W�X�g�����쐬���鎖���ł��āADocker�C���[�W�ȊO�̐��ʕ����ꏏ��Docker�C���[�W��ۑ�����T�[�r�X�Ɠ��l�ɗ��p���邱�Ƃ��ł���悤�ɂȂ�܂��B

## VMWare Harbar ���W�X�g��

VMware�́ADocker�̃G�R�V�X�e�����ł̓��W���[�v���[���[�ƂƂ炦���Ă��Ȃ���������܂��񂪁A���Ђ͊m���ɂ��̃G�R�V�X�e���̈���ɂȂ����܂��B[Harbar���W�X�g��](https://vmware.github.io/harbor/)�́AVMware���o����Docker�C���[�W���W�X�g���̓����ł��B���̃��W�X�g���́ADocker�̊�Տ�ɃR���e�i�ō\�z����Ă��܂����A�Z�L�����e�B��ID�Ǘ��@�\���ǉ�����Ă��܂��B�܂��A�P��z�X�g�ŕ����̃��W�X�g�����T�|�[�g���Ă��܂��B

__�x�X�g�ȃ��[�X�P�[�X:__ Harbar���d�����Ă���̂́A�Z�L�����e�B�ƃ��[�U�[�Ǘ��ŁA���̑��̃��W�X�g���ł͂��̂悤�ȋ@�\�͒񋟂���Ă��Ȃ��ׁA��Ƃ����߂鉿�l�̍������W�X�g���̋@�\�ƂȂ��Ă��܂��B��Ƃł̗��p�ɍœK�ł��BHarbar��Docker�̊�Տ�œ������Ƃ��A�ǂ�Docker���ɂ��C���X�g�[�����ȒP�ł��邱�Ƃ����ڂɒl���܂��B�J���҂��Z�L�����e�B���C���^�[�l�b�g�Ɍq���邱�Ƃ��ł��Ȃ��I�t���C���̃V�X�e���ł��C�y�ɓW�J���邱�Ƃ��ł��邱�Ƃ��A�|�C���g�ł��B

# ���_

��ԍŏ��̌����ۑ�́A�T�[�r�X�ł������A�I���v���~�X���A�������Ƃ������̓W�J���@�̎�ނȂǂ��܂񂾂ǂ������^�C�v�̃��W�X�g���𗘗p���邩�Ƃ������ƁG�����āA�����̃A�N�Z�X�����͂ǂ��Ȃ��Ă���̂��Ƃ������ƁG�����āA���̑��̃Z�L�����e�B�I�v�V�������ǂ��������̂����邩�Ƃ������ƁB

�������A�K�v�ȗv���ɍ��������������W�X�g����I�Ԃ��Ƃ́A�ǂ������v����D�悷�邩�ɂ�茈�܂��Ă��܂��B�������A��R�̑I�����̒�����A���̑g�D�Ƀ}�b�`�����o�����X�̗ǂ����W�X�g����������͓̂���Ȃ��ł��傤�B

���҂ɂ��āF���B���X�E�p���[��Medavie�u���[�N���X�̃G���^�[�v���C�Y�A�[�L�e�N�g�ł��B�ނ̏œ_�́A�R�A�E�R���s���[�e�B���O�iIaaS�́j�AID����уA�N�Z�X�Ǘ��A�A�v���P�[�V�����v���b�g�t�H�[���iPaaS�́j�A����јA���z�M�Ȃǂ̎�v����ɂ�����N���E�h�����ƋZ�p�v��ł��B