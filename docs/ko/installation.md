## Windows와 macOS 설치
Binary 형식의 설치 파일 (Windows 64bit 전용)과 macOS Apple Silicon을 제공하고 있습니다. 아래 링크에서 다운로드 받으세요.

[BARAM V24.4.0 Windows 설치파일 ›](https://d3c6e16xufx1gb.cloudfront.net/BARAM-24.4.0-setup.exe){: .btn .btn-purple .text-center .fs-5 onclick="trackDownload('BARAM-24.4.0-setup.exe')"}

**NOTE: macOS는 [*open-mpi*](https://formulae.brew.sh/formula/open-mpi) Homebrew Formula 가 설치되어 있어야 합니다.**

[Download BARAM v24.4.0 Disk Image(.dmg) for macOS with Apple Silicon ›](https://d3c6e16xufx1gb.cloudfront.net/BARAM-24.4.0.dmg){: .btn .btn-blue .text-center .fs-5onclick="trackDownload('BARAM-24.4.0.dmg')"}

## 지원 OS
* Windows 10 or newer
* macOS 10.14 or newer (Apple Silicon only)
* Ubuntu 20.04 or newer
* CentOS 8.2 or alternatives ( Rocky Linux, AlmaLinux, ... )
* OpenSUSE Leap 15.4
* Linux Mint 21 "Vanessa"

## 사전에 설치되어야 하는 소프트웨어

* Python *3.9.x*
* [MS-MPI](https://docs.microsoft.com/en-us/message-passing-interface/microsoft-mpi) 10.0 or newer ( Windows Only )
* OpenMPI 4.1 or newer ( Linux, macOS )
* GNU C Compiler or any other C Compiler ( Linux, macOS )

## BARAM 소스코드 다운로드

<ul>
  {% assign sorted_posts = site.categories.installation | sort: 'title' %}
  {% for post in sorted_posts %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


## Paraview [선택사항]

*BaramFlow* has a menu that can launch [*ParaView*](https://www.paraview.org/) for convenience.
If *ParaView* is installed in the system, this menu launches *ParaView* in the case foler.
