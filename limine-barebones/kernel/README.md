# Limine Bare Bones

## Progress
Followed the tutorial for a succesful boot

### PrerequisitesL
1. Linux Dev Environment
2. qemu system binary
3. make (gmake)

### To Run
`
git clone https://github.com/not-hexil/helOS.git
cd limine-barebones
make all
chmod +x makeISO.sh
./makeISO.sh
qemu-system-x86_64 -cdrom image.iso -m 512M -serial stdio
`

### Expected Result
A gradient screen upon successful boot.

## To Do
1. Codebase analysis
2. Further refinement following the limine repository
