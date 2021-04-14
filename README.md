# fricas_drawfe :construction: :rocket:
More frontends for FriCAS plotting routines (``draw``).

In order to provide other frontends than the built-in (X11 based) 
comparatively few changes to ``view2D.spad`` and ``view3D.spad`` are
necessary. To avoid confusion the files were (temporarily) renamed to 
``view2D+.spad`` and ``view3D+.spad`` respectively. 


> Initial changes to ``view2D.spad`` and ``view3D.spad``
> see [Commit: d21784c](https://github.com/nilqed/fricas_drawfe/commit/d21784c9c808d80c02e8c8272f2b49255cb86566)


---

For the demo you have to install at least ``gnuplot-qt``:


        $ sudo apt install gnuplot-qt

	$ apt list gnuplot*
	Listing... Done
	gnuplot/bionic,bionic 5.2.2+dfsg1-2ubuntu1 all
	gnuplot-data/bionic,bionic,now 5.2.2+dfsg1-2ubuntu1 all [installed,automatic]
	gnuplot-doc/bionic,bionic 5.2.2+dfsg1-2ubuntu1 all
	gnuplot-mode/bionic,bionic 1:0.7.0-1 all
	gnuplot-nox/bionic 5.2.2+dfsg1-2ubuntu1 amd64
	gnuplot-qt/bionic,now 5.2.2+dfsg1-2ubuntu1 amd64 [installed]
	gnuplot-x11/bionic 5.2.2+dfsg1-2ubuntu1 amd64


