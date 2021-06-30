Download and Installation
============================


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


CRISPR-BETS Web online version
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

	- Please visit http://bioinfor.yzu.edu.cn/crisprbets/

		.. image:: _static/main_window_online.png


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



CRISPR-BETS Desktop version
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

	- **Install via precompiled file(recommend)**

		- **1. Download CRISPR-BETS precompiled file**

			`Download Win Version`_.

				..  _`Download Win Version`: https://github.com/yuechaowu/CRISPR-BETS_desktop/releases/download/V1.0/CrisprBaseETS_win_package.zip

			`Download macOS Version`_.

				..  _`Download macOS Version`: https://github.com/yuechaowu/CRISPR-BETS_desktop/releases/download/V1.0/CrisprBaseETS_macos_package.zip

			`Download Linux Version`_.

				..  _`Download Linux Version`: https://github.com/yuechaowu/CRISPR-BETS_desktop/releases/download/V1.0/CrisprBaseETS_linux_package.zip


		- **2. Installation**

			CRISPR-BETS Desktop version was written in javascript on the Electron framework, so there is no need to install other dependencies and complicated installation process, just unzip it!

			**1. Unzip the downloaded compressed file.**

			**2. Enter the Unziped file directory.**


			.. attention::  Step 3 is different for different operating systems.

			**3. (under window) Find the CRISPR-BETS icon and double-click it.**  
				.. image:: _static/CRISPR-BETS_icon.png


			**3 (under macOS)  Find the CRISPR-BETS icon and drag it to Applications folder, Open the terminal and enter the following command.**  

				.. image:: _static/CRISPR-BETS_drag.png
				.. code-block:: bash

					 sudo xattr -d com.apple.quarantine  /Applications/CrisprBaseETS.app


			**3 (under Linux)  Open the terminal and enter the following command.**
				.. code-block:: bash

					 THE CRISPR-BETS unzipped directory/CRISPR-BETS


			**4. Show main window, Done！**

				.. image:: _static/main_window.png

	- **Install via source code**

	.. code-block:: bash

		 git clone https://github.com/zhangtaolab/CRISPR-BETS_desktop.git
		 cd CRISPR-BETS_desktop
		 npm install electron@11.2.0 -g
		 npm install
		 electron .





			
				
			


