# Limine Bare Bones

## Progress
Followed the tutorial for a succesful boot

### PrerequisitesL
1. Linux Dev Environment
2. qemu system binary
3. make (gmake)

### To Run
`
git clone https://github.com/not-hexil/helOS.git<br>
cd limine-barebones<br>
make all<br>
chmod +x makeISO.sh<br>  
./makeISO.sh<br>
qemu-system-x86_64 -cdrom image.iso -m 512M -serial stdio  
`

### Expected Result
A gradient screen upon successful boot.
![Output](image.png)
## To Do
1. Codebase analysis
2. Further refinement following the limine repository
