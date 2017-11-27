OCR @ Windows - pirmā daļa:
===========================

  1. Atvērt konsoli `openalpr-custom-built` mapē.
  2. Jāsagatavo simboli no izgriezto numuru bildēm:  
     
     ```
     classifychars <country> <input_directory> <output_directory>
     # ex: ./openalpr-utils-classifychars.exe eu ../____TRAINING/izgrieztie-numuri/GOOD/ ../____TRAINING/_____RESULT2/classifychars/
     ```
     
     1. Izvēlēties, kuru numura variāciju izmantos priekš klasifikācijas (parasti pirmā ir vislabākā)
         - <kbd><-</kbd>, <kbd>-></kbd>, lai pavirzītos pa kreisi/labi
         - <kbd>SPACE</kbd>, lai pieņemtu izvēli
     2. <kbd>ENTER</kbd> jāspiež, lai aktivizētu simbolu klasificēšanu
     3. Simbolu klasificēšana:
         - <kbd>A-Z</kbd> (lielie), lai pieteiktu simbolu
         - <kbd>SPACE</kbd>, lai izlaistu simbolu
             - Ieteicams izlaist ļoti nekvalitatīvus simbolus, vai, ja uzķer divus kopā vai tml.
     4. <kbd>S</kbd>, lai saglabātu klasificētos simbolus
     5. <kbd>N</kbd>, lai pārietu uz nākamo numuru
  3. (ja ir) Jāsagatavo simboli no fonta/simbolu bildēm:
     1. Izveidot bildi, kurā ir visi simboli kopā, no labās uz kreiso (var dalīties rindās)
     2. Izveidot teksta failu, kurā ir uzskaitīts (bez atstarpēm/rindām) kādi simboli un kādā secībā ir atrodami bildēs
     3. 
