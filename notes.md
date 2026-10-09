#Notes

## The bug was in the matches function where it only finds the exact term in notes using '===' I replace it with the .include() function as presented: function matches(notes, term) {return notes.filter((note) => note.text.includes(term));}


