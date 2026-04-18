name: Generate ASCII Artwork

on:
  push:


jobs:
  ascii-job:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v4

      - name: Install Cowsay Program
        run: sudo apt-get install cowsay -y

      - name: Execute Cowsay CMD
        run: cowsay -f dragon "Run for cover, I am a DRAGON.....RAWS" >> dragon.txt

      - name: Test File Exists 
        run: grep -i "dragon" dragon.txt

      - name: Read  File  
        run: car dragon.txt
        
      - name: Checkout Repo File Exists 
        run: ls           