# PigLatin-Translator
# PigLatin-Translator
pyg = 'ay'

original = raw_input('Enter a word:')
word=original.lower();
first=original[0];
new_word=word + first + pyg;

    
if len(original) > 0 and original.isalpha():
    print original
else:
    print 'empty'
    
s=new_word;
new_word=s[1:len(new_word)];
print new_word; 
