git pull https://github.com/avianage/codedump.git

cd codedump

u+x chmod install.sh

./install.sh



echo "Installing Geany"

sudo apt install geany -y

geany --version

echo "Installing Python"

sudo apt install python -y

python --version

echo "Installing C++"

sudo apt-get install g++

echo "Installed g++"

sudo apt-get install build-essential -y

g++ --version

echo "Installing Java"

sudo apt install default-jre -y

java --version
