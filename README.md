# Ubuntu 使用

## opencv

1. ippicv——将对用的文件下载完成后放入 path-to-opencv/.cache/ippicv即可
2. boost&vgg——修改对应cmake文件，并将将手动下载文件放入 path-to-opencv-contrib/modules/xfeatures2d/src


## pcl

1. pcl1.9.0 & vtk8.1.2

## vim

1. install vundle:

    ```bash
    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    ```

2. install YCM

    ```bash
    ./install.py --clang-completer
    ````

3. move config file to right place<.vimrc & .ycm_extra_conf.py>
