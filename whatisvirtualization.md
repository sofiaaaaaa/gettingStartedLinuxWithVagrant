![](http://cfile4.uf.tistory.com/image/174A1D4F4FBDE8EB17CBE7)

# 가상화란?

---

* 1960년대 메인프레임에서 시작.
* 시스템 활용도를 높이기 위해 사용시작.
* 물리적인 하드웨어 자원을 소프트웨어 자원으로 변환하여 제공.
* 서버 가상화에서 vm(virtual machine)은 guest로 불림.

## 가상화의 종류

* 서버 가상화
* 데스크탑 가상화
* 스토리지 가상화
* 네트워크 가상화

![](http://www.centergrid.com/wp-content/uploads/2016/09/Types-of-virtualization.png)

## hypervisor란?

* 물리 서버의 CPU와 디스크에 직접 상호작용하며, 가상 서버의 플랫폼 역확을 한다.
* 각각의 가상 서버(guest)들을 완전히 독립적으로 운영토록 한다.
* 물리 서버의 자원을 모니터링하여, 가상 서버에서 애플리케이션이 구동될 때, 물리 서버의 자원을 적절한 가상 서버에 할당해 준다

## hypervisor 사용방식에 따른 분류

* type1
    * 일반적으로 하이퍼바이저(Hypervisor)형 가상화 또는 Bare metal 이라고 불림.
    * 하이퍼바이저를 하드웨어상에 직접 동작 시키는 방식.
    * 호스트형 가상화에 비행 오버헤드가 적음.
    * 별도의 관리 프로그램이 필요.
![](http://cfs2.tistory.com/image/5/tistory/2008/10/07/22/13/48eb6079143ef)

![](https://i0.wp.com/blog.pasion.kr/wp-content/uploads/2014/09/VMware-ESXi-2.jpg?zoom=2&resize=261%2C146&ssl=1)

![](http://www.poweronplatforms.com/wp-content/uploads/2016/11/Hyper-V.png)

![](https://i1.wp.com/files.cyberciti.biz/cbzcache/3rdparty/kvm-logo.png?zoom=2)

![](https://www.cl.cam.ac.uk/research/srg/netos/projects/archive/xen/graphics/xenlogo.gif)

* type2
    * 일반적으로 호스트(Hosted)형 가상화라고 불림.
    * 하이퍼바이저를 하드웨어상의 hostOS 위에 동작 시키는 방식.
    * type1에 비해 오버헤드가 큼.
![](http://cfs2.tistory.com/image/8/tistory/2008/10/07/22/13/48eb60788b674)

![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Virtualbox_logo.png/200px-Virtualbox_logo.png)

![](http://img.appnee.com/appnee.com/VMware-Workstation-Universal-License-Keys-for-Win-Lin-1.png)

### Link

---

[가상화란?](http://www.goodus.com/knowledge_pds/1%ED%99%94_%EA%B0%80%EC%83%81%ED%99%94%EB%9E%80%20%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80(3).pdf) <br>
[타입에 따른 분류](http://virtualhive.tistory.com/22) <br>
[Hypervisor](https://en.wikipedia.org/wiki/Hypervisor)
