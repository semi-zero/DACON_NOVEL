A. 사용된 소설 및 작가 (소설 및 작가는 대회 종료 후 공개하길 제안합니다.)
  [http://www.gutenberg.org/]
  0 : Charles Dickens
    a. Oliver Twist
    b. A Tale of Two Cities
    c. A Christmas Carol in Prose
    +. Great Expectations
    +. David Copperfield
  1 : Jane Austen
    a. Pride and Prejudice
    b. Sense and Sensibility
    c. Emma
    +. Northanger Abbey
    +. Persuasion
    +. Mansfield Park
  2 : Arthur Conan Doyle
    a. The Adventures of Sherlock Holmes
    b. A Study in Scarlet
    c. The Lost World
    +. The Hound of the Baskervilles
    +. The Sign of the Four
    +. The Valley of Fear
    +. The White Company
    ++. Memoirs of Sherlock Holmes
    ++. His last Bow
  3 : Dostoevskii
    a. The Brothers Karamazov
    b. Crime and Punishment
    c. Notes from the Underground
    ++. The Idiot
    ++. The_Possessed
  4 : Robert Louis Stevenson
    a. The Strange Case of Dr. Jekyll and Mr. Hyde
    b. Treasure Island
    c. Kidnapped
    +. Prince_Otto
    +. The Black Arrow
    +. The Master of Ballantrae
    +++. New_Arabian_Nights
    +++. The_Merry_Men

B. 전처리
 - 비식별화 : 비식별화를 위하여 일부 고유 명사가 'odin'으로 변경되었습니다.
 - test_x의 text는 삼십 단어 이상으로 구성됩니다.
 - train의 text는 다섯 단어 이상으로 구성됩니다.
 - 모든 text는 사백 단어를 초과하지 않습니다.
 - 'chapter'가 들어간 문장을 제거했습니다.

C. 데이터 모양
 - train.csv(14MB) : (54879, 3)
 - test_x.csv(10MB) : (19617, 2)
 - sample_submission.csv(1MB) : (19617, 6)

C. 평가산식 : logloss

D. 외부 데이터 사용
- 외부 데이터 사용이 불가합니다.