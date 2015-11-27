1
2
3
4
5
6
7
8
mkdir VC_CORE.github.com
cd VC_CORE.github.com
git init
echo "Hello" > index.html
git add index.html
git commit -m "first commit"
git remote add origin git@github.com:VC_CORE/VC_CORE.github.com.git
git push -u origin master
