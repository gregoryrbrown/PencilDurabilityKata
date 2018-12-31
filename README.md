# PencilDurabilityKata
Kata simulating a pencil writing on paper and degrading over time.


Assumption: The deliverable for this will be gthe business logic for this, not a particular executable, but one could be created in the development of the business logic.

Assumption: The erasing will have an effect on a paper. That is, a pencil acts upon a paper.

Assumption: The erasing of an edit that has "@" in it will be done by telling the pencil to erase the substring with the "@" symbol in it, rather than having to find it by checking if the "@" is part of the specified string to erase.

Assumption: The pencil will only be told to edit over the last erasure. Actually, it will be one command "Erase and Replace". 

Assumption: When the pencil cannot erase all of the text for an erase and replace, it should what? Let's back up and just write over whatever is left and leave "@" there in the places that can't be erased.

Assumption: The Sharpen operation is basically a reset operation on the pencil point. Also, a decrement of the length. When the length hits zero, it cannot be sharpened.



