
18. Since it simply prints out something, it can be set to 'void' return type: public void listAllFiles()

19. Yes, we could. However, that wouldn't be a smart way to do this, since we don't know how many elements the user might want to add. If the user adds 100 files, we'd have to write 100 printsln statements. So instead, just use a loop 
that repeats as many times as the files of elements in the ArrayList
