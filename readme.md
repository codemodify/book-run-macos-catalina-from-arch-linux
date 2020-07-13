# ![](https://fonts.gstatic.com/s/i/materialiconsoutlined/flare/v4/24px.svg) Publish Books on Amazon
>__The missing guide on running macOS Catalina on Arch Linux__

>__This is designed to be hands on and to the point without any BS__

>__Book updated on May 25 2020__



# ![](https://fonts.gstatic.com/s/i/materialicons/build/v5/24px.svg) Tools
- Run in terminal: `yay -S unrar`
- Run in terminal: `yay -S linux-headers`
- Run in terminal: `yay -S vmware-workstation`
- Run in terminal: `sudo systemctl start vmware-networks.service`
- Run in terminal: `sudo systemctl start vmware-usbarbitrator.service`
- Run in terminal: `sudo systemctl start vmware-hostd.service`
- Run in terminal: `sudo modprobe -a vmw_vmci vmmon`
- Open in Browser and download:
	- https://drive.google.com/drive/folders/1mUPKPG2Iq5qPUovrmSNFiAffqjdYhPzp?usp=sharing
	- OR
	- https://www.mediafire.com/folder/6p5rv8jd50cua/macOS_Catalina_10.15.3_by_Geekrar_(One_Full)
	- OR
	- https://drive.google.com/drive/folders/1hao4u-vmaz30fEUDMwsKYMwx2LRSWQuH
	- it is the macOS Catalina 10.15.3 ISO for VMware & VirtualBox - compressed, zipped, and encrypted
-  Run in terminal: `unrar e "macOS Catalina ISO by Geekrar.rar"`
	- the password is: `Geekrar.com`


# ![](https://fonts.gstatic.com/s/i/materialicons/publish/v5/24px.svg) Publish

- Write the MD (markdown format) book

- Run in terminal: `pandoc readme.md -o book.epub --metadata title="Publishing books on Amazon from Arch Linux"`

- Run in terminal: `kindlegen book.epub`


- Take the generated "book.mobi" and upload it to https://kdp.amazon.com



# ![](https://fonts.gstatic.com/s/i/materialicons/code/v5/24px.svg) Source Code

https://github.com/codemodify/publish-books-amazon-arch-linux
