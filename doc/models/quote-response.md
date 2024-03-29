
# Quote Response

## Structure

`QuoteResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Docs` | [`List<QuoteDoc>`](../../doc/models/quote-doc.md) | Required | - | List<QuoteDoc> getDocs() | setDocs(List<QuoteDoc> docs) |
| `Total` | `int` | Required | - | int getTotal() | setTotal(int total) |
| `Limit` | `int` | Required | - | int getLimit() | setLimit(int limit) |
| `Offset` | `int` | Required | - | int getOffset() | setOffset(int offset) |
| `Page` | `int` | Required | - | int getPage() | setPage(int page) |
| `Pages` | `int` | Required | - | int getPages() | setPages(int pages) |

## Example (as JSON)

```json
{
  "docs": [
    {
      "_id": "5cd96e05de30eff6ebcce7e9",
      "dialog": "Deagol!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7e9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7ea",
      "dialog": "Deagol!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7ea"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7eb",
      "dialog": "Deagol!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7eb"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7ec",
      "dialog": "Give us that! Deagol my love",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7ec"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7ed",
      "dialog": "Why?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca7",
      "id": "5cd96e05de30eff6ebcce7ed"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7ee",
      "dialog": "Because', it's my birthday and I wants it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7ee"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7ef",
      "dialog": "Arrghh!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca7",
      "id": "5cd96e05de30eff6ebcce7ef"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f0",
      "dialog": "They cursed us!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7f0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f1",
      "dialog": "Murderer!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7f1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f2",
      "dialog": "'Murderer' they called us. They cursed us and drove us away.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7f2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f3",
      "dialog": "Pull it in! Go on, go on, go on, pull it in!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7f3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f4",
      "dialog": "Oh Smeagol I've got one! I've got a fish Smeagol, Smeagol!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca7",
      "id": "5cd96e05de30eff6ebcce7f4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f5",
      "dialog": "My precious.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7f5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f6",
      "dialog": "Gandalf?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce7f6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f7",
      "dialog": "Oooohhh!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce7f7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f8",
      "dialog": "Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce7f8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7f9",
      "dialog": "Aaaahh!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce7f9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7fa",
      "dialog": "and cool, so nice for feet, and we only wish to catch a fish, so juicy sweet.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7fa"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7fb",
      "dialog": "Gimli!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce7fb"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7fc",
      "dialog": "My precious!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7fc"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7fd",
      "dialog": "Wake up! Wake up! Wake up sleepies! We must go, yes, we must go at once.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7fd"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7fe",
      "dialog": "Haven't you had any sleep Mr Frodo?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce7fe"
    },
    {
      "_id": "5cd96e05de30eff6ebcce7ff",
      "dialog": "And we forgot the taste of bread, the sound of trees and the softness of the wind. We even forgot our own name.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce7ff"
    },
    {
      "_id": "5cd96e05de30eff6ebcce800",
      "dialog": "Gollum' Gollum' Gollum', and we wept precious. We wept to be so alone.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce800"
    },
    {
      "_id": "5cd96e05de30eff6ebcce801",
      "dialog": "Not before Mr Frodo's had something to eat.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce801"
    },
    {
      "_id": "5cd96e05de30eff6ebcce802",
      "dialog": "No time to lose silly!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce802"
    },
    {
      "_id": "5cd96e05de30eff6ebcce803",
      "dialog": "Come on! Must go! No time!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce803"
    },
    {
      "_id": "5cd96e05de30eff6ebcce804",
      "dialog": "And I've gone and had too much. It must be getting late.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce804"
    },
    {
      "_id": "5cd96e05de30eff6ebcce805",
      "dialog": "No, it isn't. It isn't midday yet. The days are growing darker.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce805"
    },
    {
      "_id": "5cd96e05de30eff6ebcce806",
      "dialog": "Here.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce806"
    },
    {
      "_id": "5cd96e05de30eff6ebcce807",
      "dialog": "What about you?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce807"
    },
    {
      "_id": "5cd96e05de30eff6ebcce808",
      "dialog": "Oh no, I'm not hungry, leastways not for lembas bread.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce808"
    },
    {
      "_id": "5cd96e05de30eff6ebcce809",
      "dialog": "Sam!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce809"
    },
    {
      "_id": "5cd96e05de30eff6ebcce80a",
      "dialog": "Aragorn!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce80a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce80b",
      "dialog": "Now come the days of the King. May they be blessed.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce80b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce80c",
      "dialog": "This day does not belong to one man, but to all. Let us together rebuild this world, that we may share in the days of peace.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce80c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce80d",
      "dialog": "Et E'rello Endorenna ut'lien. Sinome maruvan ar Hildinyar tenn' Ambar-metta!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce80d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce80e",
      "dialog": "Hannon le.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce80e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce80f",
      "dialog": "My friends, you bow to no-one.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce80f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce810",
      "dialog": "And thus it was a Fourth Age of Middle Earth began. And the Fellowship of the Ring, though eternally bound by friendship and love was ended. Thirteen months to the day since Gandalf sent us on our long journey we find ourselves looking upon a familiar sight.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce810"
    },
    {
      "_id": "5cd96e05de30eff6ebcce811",
      "dialog": "Alright!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce811"
    },
    {
      "_id": "5cd96e05de30eff6ebcce812",
      "dialog": "We were home.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce812"
    },
    {
      "_id": "5cd96e05de30eff6ebcce813",
      "dialog": "Hey watch the pumpkin.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce813"
    },
    {
      "_id": "5cd96e05de30eff6ebcce814",
      "dialog": "The journey home.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce814"
    },
    {
      "_id": "5cd96e05de30eff6ebcce815",
      "dialog": "Oh alright, but we don't have that much left. We have to be careful or we are going to run out. You go ahead and eat that Mr Frodo. I've rationed it, there should be enough.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce815"
    },
    {
      "_id": "5cd96e05de30eff6ebcce816",
      "dialog": "Come Hobbitses, very close now. Very close to Mordor. No safe places here. Hurry.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce816"
    },
    {
      "_id": "5cd96e05de30eff6ebcce817",
      "dialog": "It's good. Definitely from the Shire. Longbottom leaf eh?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce817"
    },
    {
      "_id": "5cd96e05de30eff6ebcce818",
      "dialog": "uhh huh, I feel like I'm back at the Green Dragon.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce818"
    },
    {
      "_id": "5cd96e05de30eff6ebcce819",
      "dialog": "Mmmm, Green Dragon!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce819"
    },
    {
      "_id": "5cd96e05de30eff6ebcce81a",
      "dialog": "For what?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce81a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce81b",
      "dialog": "Goodnight lads.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc8f",
      "id": "5cd96e05de30eff6ebcce81b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce81c",
      "dialog": "Welcome, my lords to Isengard!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce81c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce81d",
      "dialog": "You young rascals. A merry hunt you've led us on and now we find you feasting and ' and smoking!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce81d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce81e",
      "dialog": "Hmm?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce81e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce81f",
      "dialog": "Only, you've never done a hard day's work.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce81f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce820",
      "dialog": "Ahaha!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce820"
    },
    {
      "_id": "5cd96e05de30eff6ebcce821",
      "dialog": "How do you pick up the threads of an old life? How do you go on, when in your heart you begin to understand there is no going back? There are some things that time cannot mend. Some hurts that go too deep, that have taken hold.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce821"
    },
    {
      "_id": "5cd96e05de30eff6ebcce822",
      "dialog": "Mr Frodo? What is it?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce822"
    },
    {
      "_id": "5cd96e05de30eff6ebcce823",
      "dialog": "It's been four years to the day since Weathertop, Sam. It's never really healed.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce823"
    },
    {
      "_id": "5cd96e05de30eff6ebcce824",
      "dialog": "A mug of ale in my hand. Putting my feet up on a settle after a hard day's work.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce824"
    },
    {
      "_id": "5cd96e05de30eff6ebcce825",
      "dialog": "\"There and Back Again, a Hobbit's tale\" by Bilbo Baggins and \"The Lord of the Rings\" by Frodo Baggins. You finished it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce825"
    },
    {
      "_id": "5cd96e05de30eff6ebcce826",
      "dialog": "Not quite. There's room for a little more.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce826"
    },
    {
      "_id": "5cd96e05de30eff6ebcce827",
      "dialog": "Bilbo once told me his part in this tale would end. That each of us must come and go in the telling. Bilbo's story was now over. There would be no more journeys for him, save one.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce827"
    },
    {
      "_id": "5cd96e05de30eff6ebcce828",
      "dialog": "To the harbour, Bilbo. The elves have accorded you a special honour. A place on the last ship to leave Middle Earth.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce828"
    },
    {
      "_id": "5cd96e05de30eff6ebcce829",
      "dialog": "Salted pork",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce829"
    },
    {
      "_id": "5cd96e05de30eff6ebcce82a",
      "dialog": "Hobbits!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce82a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce82b",
      "dialog": "We're under orders from Treebeard who's taken over management of Isengard.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce82b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce82c",
      "dialog": "Tell me again lad, where are we going?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc38",
      "id": "5cd96e05de30eff6ebcce82c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce82d",
      "dialog": "Frodo, any chance of seeing that old Ring of mine again? The one I gave you?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc38",
      "id": "5cd96e05de30eff6ebcce82d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce82e",
      "dialog": "Hoooom, young master Gandalf, I'm glad you've come. Wood and water, stock and stone I can master, but there is a Wizard to manage here locked in his tower",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d533844dc4c55e47afed",
      "id": "5cd96e05de30eff6ebcce82e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce82f",
      "dialog": "We are sitting on a field of victory enjoying a few well earned comforts, The salted pork is particularly good.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce82f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce830",
      "dialog": "Show yourself.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce830"
    },
    {
      "_id": "5cd96e05de30eff6ebcce831",
      "dialog": "Well then let's just have his head and be done with it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce831"
    },
    {
      "_id": "5cd96e05de30eff6ebcce832",
      "dialog": "Be careful. Even in defeat, Saruman is dangerous.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce832"
    },
    {
      "_id": "5cd96e05de30eff6ebcce833",
      "dialog": "You have fought many wars and slain many men Theoden King and made peace afterwards. Can we not take counsel together as we once did, my old friend?Can we not have peace you and I?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea4",
      "id": "5cd96e05de30eff6ebcce833"
    },
    {
      "_id": "5cd96e05de30eff6ebcce834",
      "dialog": "We shall have peace'. We shall have peace when you answer for the burning of the Westfold and the children that lie dead there! We shall have peace when the lives of the soldiers whose bodies were hewn even as they lay dead against the gates of the Hornburg' are avenged! When you hang from a gibbet for the sport of your own crows' we shall have peace!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce834"
    },
    {
      "_id": "5cd96e05de30eff6ebcce835",
      "dialog": "Gibbets and crows! Dotard! What do you want Gandalf Grahame? Let me guess' the key of Orthanc? Or perhaps the keys of Barad D'r itself? Along with the crowns of the seven Kings and the rods of the Five Wizards!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea4",
      "id": "5cd96e05de30eff6ebcce835"
    },
    {
      "_id": "5cd96e05de30eff6ebcce836",
      "dialog": "No, we need him alive. We need him to talk.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce836"
    },
    {
      "_id": "5cd96e05de30eff6ebcce837",
      "dialog": "I'm sorry uncle. I'm afraid I lost it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce837"
    },
    {
      "_id": "5cd96e05de30eff6ebcce838",
      "dialog": "Your treachery has already cost many lives. Thousands more are now at risk. But you could save them Saruman. You were deep in the enemy's counsel.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce838"
    },
    {
      "_id": "5cd96e05de30eff6ebcce839",
      "dialog": "I Aear c'n ven na mar.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebcce839"
    },
    {
      "_id": "5cd96e05de30eff6ebcce83a",
      "dialog": "I think I'm quite ready for another adventure.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc38",
      "id": "5cd96e05de30eff6ebcce83a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce83b",
      "dialog": "Farewell my brave Hobbits. My work is now finished. Here at last, on the shores of the sea, comes the end of our Fellowship. I will not say do not weep for not all tears are an evil. It is time Frodo.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce83b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce83c",
      "dialog": "What does he mean?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce83c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce83d",
      "dialog": "Oh! Well here is a sight I have never seen before.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc38",
      "id": "5cd96e05de30eff6ebcce83d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce83e",
      "dialog": "The power of the three rings is ended. The time has come for the dominion of men.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd06",
      "id": "5cd96e05de30eff6ebcce83e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce83f",
      "dialog": "Oh, pity. I would have like to have held it one last time.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc38",
      "id": "5cd96e05de30eff6ebcce83f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce840",
      "dialog": "We set out to save the Shire, Sam, and it has been saved. But not for me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce840"
    },
    {
      "_id": "5cd96e05de30eff6ebcce841",
      "dialog": "You don't mean that. You can't leave.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce841"
    },
    {
      "_id": "5cd96e05de30eff6ebcce842",
      "dialog": "So you have come here for information. I have some for you. Something festers in the heart of Middle Earth. Something that you have failed to see. But the great eye has seen it! Even now he presses his advantage. His attack will come soon. You are all going to die! But you know this don't you Gandalf? You cannot think that this Ranger will ever sit upon the throne of Gondor. This exile, crept from the shadows will never be crowned King. Gandalf does not hesitate to sacrifice those who are closest to him' those he professes to love! Tell me, what words of comfort did you give the Halfling before you sent him to his doom? The path that you have set him on can only lead to death.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea4",
      "id": "5cd96e05de30eff6ebcce842"
    },
    {
      "_id": "5cd96e05de30eff6ebcce843",
      "dialog": "Save your pity and your mercy. I have no use for it!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea4",
      "id": "5cd96e05de30eff6ebcce843"
    },
    {
      "_id": "5cd96e05de30eff6ebcce844",
      "dialog": "Saruman! Your staff is broken!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce844"
    },
    {
      "_id": "5cd96e05de30eff6ebcce845",
      "dialog": "Grima! You need not follow him! You were not always as you are now. You were once a man of Rohan. Come down.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce845"
    },
    {
      "_id": "5cd96e05de30eff6ebcce846",
      "dialog": "I've heard enough! Shoot him! Stick an arrow in his gob!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce846"
    },
    {
      "_id": "5cd96e05de30eff6ebcce847",
      "dialog": "The last pages are for you Sam.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce847"
    },
    {
      "_id": "5cd96e05de30eff6ebcce848",
      "dialog": "Free? He will never be free!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea4",
      "id": "5cd96e05de30eff6ebcce848"
    },
    {
      "_id": "5cd96e05de30eff6ebcce849",
      "dialog": "No!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9d",
      "id": "5cd96e05de30eff6ebcce849"
    },
    {
      "_id": "5cd96e05de30eff6ebcce84a",
      "dialog": "My dear Sam, you cannot always be torn in two. You will have to be one and whole for many years. You have so much to enjoy and to be and to do. Your part in the story will go on.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce84a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce84b",
      "dialog": "Well, I'm back.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce84b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce84c",
      "dialog": "I didn't think it would end this way.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce84c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce84d",
      "dialog": "End? No, the journey doesn't end here. Death is just another path, one that we all must take. The grey rain curtain of this world rolls back and all turns to silvered glass. And then you see it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce84d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce84e",
      "dialog": "A man of Rohan? What is the house of Rohan but a thatched barn where brigands drink in the reek and their brats roll on the floor with the dogs? The victory at Helms Deep does not belong to you Theoden Horse Master. You are a lesser son of greater sires!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea4",
      "id": "5cd96e05de30eff6ebcce84e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce84f",
      "dialog": "Grima! Come down! Be free of him!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce84f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce850",
      "dialog": "No! Come down, Saruman, and your life will be spared!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce850"
    },
    {
      "_id": "5cd96e05de30eff6ebcce851",
      "dialog": "What? Gandalf? See what?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce851"
    },
    {
      "_id": "5cd96e05de30eff6ebcce852",
      "dialog": "Rally to me! To meeee!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce852"
    },
    {
      "_id": "5cd96e05de30eff6ebcce853",
      "dialog": "Feast on his flesh.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d576844dc4c55e47afee",
      "id": "5cd96e05de30eff6ebcce853"
    },
    {
      "_id": "5cd96e05de30eff6ebcce854",
      "dialog": "I will kill you if you touch him.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce854"
    },
    {
      "_id": "5cd96e05de30eff6ebcce855",
      "dialog": "The City has fallen silent. There is no warmth left in the sun.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce855"
    },
    {
      "_id": "5cd96e05de30eff6ebcce856",
      "dialog": "It grows so cold.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce856"
    },
    {
      "_id": "5cd96e05de30eff6ebcce857",
      "dialog": "It's just the damp of the first spring rain.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce857"
    },
    {
      "_id": "5cd96e05de30eff6ebcce858",
      "dialog": "No. No it isn't.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce858"
    },
    {
      "_id": "5cd96e05de30eff6ebcce859",
      "dialog": "Well, that's not so bad.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce859"
    },
    {
      "_id": "5cd96e05de30eff6ebcce85a",
      "dialog": "White shores and beyond, a far green country under a swift sunrise.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce85a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce85b",
      "dialog": "I do not believe this darkness will endure.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce85b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce85c",
      "dialog": "Look! The Orcs, they're moving off!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce85c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce85d",
      "dialog": "Get down cur!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea4",
      "id": "5cd96e05de30eff6ebcce85d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce85e",
      "dialog": "Ah!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9d",
      "id": "5cd96e05de30eff6ebcce85e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce85f",
      "dialog": "Saruman! You were deep in the enemy's counsel. Tell us what you know!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce85f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce860",
      "dialog": "You withdraw your guard and I will tell you where your doom will be decided. I will not be held prisoner here!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea4",
      "id": "5cd96e05de30eff6ebcce860"
    },
    {
      "_id": "5cd96e05de30eff6ebcce861",
      "dialog": "Send word to all our allies and to every corner of Middle Earth that still stands free. The enemy moves against us. We need to know where he will strike.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce861"
    },
    {
      "_id": "5cd96e05de30eff6ebcce862",
      "dialog": "The filth of Saruman is washing away. Trees will come back to live here. Young trees. Wild trees.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d533844dc4c55e47afed",
      "id": "5cd96e05de30eff6ebcce862"
    },
    {
      "_id": "5cd96e05de30eff6ebcce863",
      "dialog": "Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce863"
    },
    {
      "_id": "5cd96e05de30eff6ebcce864",
      "dialog": "Bless my bark!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d533844dc4c55e47afed",
      "id": "5cd96e05de30eff6ebcce864"
    },
    {
      "_id": "5cd96e05de30eff6ebcce865",
      "dialog": "Peregrin Took. I'll take that my lad! Quickly now!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce865"
    },
    {
      "_id": "5cd96e05de30eff6ebcce866",
      "dialog": "Do not come between the Nazg'l and his prey.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d576844dc4c55e47afee",
      "id": "5cd96e05de30eff6ebcce866"
    },
    {
      "_id": "5cd96e05de30eff6ebcce867",
      "dialog": "Late as usual, pirate scum. There's knifework here needs doing. Come on you sea rats, get off your ships.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce867"
    },
    {
      "_id": "5cd96e05de30eff6ebcce868",
      "dialog": "You see Mr Frodo some luck at last!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce868"
    },
    {
      "_id": "5cd96e05de30eff6ebcce869",
      "dialog": "Move it, you slugs!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce869"
    },
    {
      "_id": "5cd96e05de30eff6ebcce86a",
      "dialog": "Come on! Faster!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce86a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce86b",
      "dialog": "Come along you scum! I'll whip you down to the bone! Come on! What have I told you. Get up! Come on you slugs! You two are going straight to the front line! Move it, come on! Fall in! Move it! Move it! Move it!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce86b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce86c",
      "dialog": "To the gate you slugs, now move it! Don't you know we're at war?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce86c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce86d",
      "dialog": "Company halt! Inspection!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce86d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce86e",
      "dialog": "You fool! No man can kill me. Die now!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d576844dc4c55e47afee",
      "id": "5cd96e05de30eff6ebcce86e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce86f",
      "dialog": "There's plenty for the both of us, may be best Dwarf win!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce86f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce870",
      "dialog": "I am no man!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce870"
    },
    {
      "_id": "5cd96e05de30eff6ebcce871",
      "dialog": "Mr Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce871"
    },
    {
      "_id": "5cd96e05de30eff6ebcce872",
      "dialog": "Sam! Help me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce872"
    },
    {
      "_id": "5cd96e05de30eff6ebcce873",
      "dialog": "Stand up Mr Frodo. Stand up!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce873"
    },
    {
      "_id": "5cd96e05de30eff6ebcce874",
      "dialog": "Get off of me! Nobody pushes me you filthy maggot! Get off of me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce874"
    },
    {
      "_id": "5cd96e05de30eff6ebcce875",
      "dialog": "Retreat! The city is breached. Fall back to the second level. Get the women and children out. Get them out. Retreat.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce875"
    },
    {
      "_id": "5cd96e05de30eff6ebcce876",
      "dialog": "Come on, come on!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce876"
    },
    {
      "_id": "5cd96e05de30eff6ebcce877",
      "dialog": "Move into the city. Kill all in your path.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce877"
    },
    {
      "_id": "5cd96e05de30eff6ebcce878",
      "dialog": "Break it up! Break it up!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce878"
    },
    {
      "_id": "5cd96e05de30eff6ebcce879",
      "dialog": "Oy! I'll have your guts if you don't shut this rabble down!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce879"
    },
    {
      "_id": "5cd96e05de30eff6ebcce87a",
      "dialog": "It's so heavy!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce87a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce87b",
      "dialog": "Oh no! What do I do?, What do I do?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce87b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce87c",
      "dialog": "Hit me! Hit me Sam! Start fighting!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce87c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce87d",
      "dialog": "Go Sam. Now!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce87d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce87e",
      "dialog": "Take them down!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce87e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce87f",
      "dialog": "Fight! Fight to the last man. Fight for your lives.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce87f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce880",
      "dialog": "Gandalf! Gandalf! Denethor has lost his mind. He's burning Faramir alive!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce880"
    },
    {
      "_id": "5cd96e05de30eff6ebcce881",
      "dialog": "Move along scum!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce881"
    },
    {
      "_id": "5cd96e05de30eff6ebcce882",
      "dialog": "Get back in the line you maggots! Get back in the line you slugs!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce882"
    },
    {
      "_id": "5cd96e05de30eff6ebcce883",
      "dialog": "Up! Quickly!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce883"
    },
    {
      "_id": "5cd96e05de30eff6ebcce884",
      "dialog": "Go back to the abyss! Fall into the nothingness that awaits you and your master!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce884"
    },
    {
      "_id": "5cd96e05de30eff6ebcce885",
      "dialog": "Do you not know death when you see it, old man?, This is my hour!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d576844dc4c55e47afee",
      "id": "5cd96e05de30eff6ebcce885"
    },
    {
      "_id": "5cd96e05de30eff6ebcce886",
      "dialog": "I can't! I can't! I can't manage the Ring, Sam. It's such a weight to carry. It's such a weight.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce886"
    },
    {
      "_id": "5cd96e05de30eff6ebcce887",
      "dialog": "We're going that way, straight as we can. There's no point carrying anything we're not sure to need.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce887"
    },
    {
      "_id": "5cd96e05de30eff6ebcce888",
      "dialog": "Mr Frodo, look. There is light and beauty up there that no shadow can touch.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce888"
    },
    {
      "_id": "5cd96e05de30eff6ebcce889",
      "dialog": "Take mine. There's a few drops left.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce889"
    },
    {
      "_id": "5cd96e05de30eff6ebcce88a",
      "dialog": "There will be none left for the return journey.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce88a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce88b",
      "dialog": "I don't think there will be a return journey Mr Frodo.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce88b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce88c",
      "dialog": "Frodo, get down! Hide!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce88c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce88d",
      "dialog": "AAAAhhh!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce88d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce88e",
      "dialog": "You have failed! The world of men will fall.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d576844dc4c55e47afee",
      "id": "5cd96e05de30eff6ebcce88e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce88f",
      "dialog": "Gandalf!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce88f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce890",
      "dialog": "Where are they?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce890"
    },
    {
      "_id": "5cd96e05de30eff6ebcce891",
      "dialog": "Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce891"
    },
    {
      "_id": "5cd96e05de30eff6ebcce892",
      "dialog": "Is there any in this rout with authority to treat with me?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d5a0844dc4c55e47afef",
      "id": "5cd96e05de30eff6ebcce892"
    },
    {
      "_id": "5cd96e05de30eff6ebcce893",
      "dialog": "We do not come to treat with Sauron, faithless and accursed. Tell your master this. The armies of Mordor must disband. He is to depart these lands, never to return.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce893"
    },
    {
      "_id": "5cd96e05de30eff6ebcce894",
      "dialog": "Let the Lord of the Black Land come forth! Let justice be done upon him!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce894"
    },
    {
      "_id": "5cd96e05de30eff6ebcce895",
      "dialog": "Courage Merry. Courage for our friends.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce895"
    },
    {
      "_id": "5cd96e05de30eff6ebcce896",
      "dialog": "Form ranks you maggots. Form ranks. Pikes in front, archers behind.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce896"
    },
    {
      "_id": "5cd96e05de30eff6ebcce897",
      "dialog": "Eomer, take your Eored down the left flank",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce897"
    },
    {
      "_id": "5cd96e05de30eff6ebcce898",
      "dialog": "Flank ready!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce898"
    },
    {
      "_id": "5cd96e05de30eff6ebcce899",
      "dialog": "Ride now, ride now! Ride! Ride for ruin and the world's ending! DEATH!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce899"
    },
    {
      "_id": "5cd96e05de30eff6ebcce89a",
      "dialog": "DEATH!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce89a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce89b",
      "dialog": "DEATH!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce89b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce89c",
      "dialog": "DEATH!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce89c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce89d",
      "dialog": "DEATH!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce89d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce89e",
      "dialog": "DEATH!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce89e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce89f",
      "dialog": "Whatever happens, stay with me. I'll look after you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce89f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a0",
      "dialog": "Gamling, follow the King's banner down the centre. Grimbold! Take your company right after you pass the wall. Forth and fear no darkness! Arise! Arise riders of Theoden. Spears shall be shaken, shields shall be splintered, a sword day, a red day ere the sun rises!!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8a0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a1",
      "dialog": "My master Sauron the Great bids thee welcome.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d5a0844dc4c55e47afef",
      "id": "5cd96e05de30eff6ebcce8a1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a2",
      "dialog": "Silence!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce8a2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a3",
      "dialog": "No!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce8a3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a4",
      "dialog": "Silence!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce8a4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a5",
      "dialog": "The Halfling was dear to thee I see. Know that he suffered greatly at the hands of his host. Who would've thought one so small could endure so much pain? And he did Gandalf, he did.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d5a0844dc4c55e47afef",
      "id": "5cd96e05de30eff6ebcce8a5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a6",
      "dialog": "You may go no further.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce8a6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a7",
      "dialog": "You will not enter Gondor",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce8a7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a8",
      "dialog": "Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce8a8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8a9",
      "dialog": "Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce8a9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8aa",
      "dialog": "Legolas, fire a warning shot past the boson's ear.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce8aa"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ab",
      "dialog": "Mind your aim.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce8ab"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ac",
      "dialog": "Oh! That's it, right, we warned you! Prepare to be boarded!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce8ac"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ad",
      "dialog": "Aha! Old Greybeard! I have a token I was bidden to show thee.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d5a0844dc4c55e47afef",
      "id": "5cd96e05de30eff6ebcce8ad"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ae",
      "dialog": "Who are you to deny us passage?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce8ae"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8af",
      "dialog": "Boarded, by you and whose army?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce8af"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b0",
      "dialog": "Forth Eorlingas!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8b0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b1",
      "dialog": "DEATH!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce8b1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b2",
      "dialog": "CHAAAAARGE!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8b2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b3",
      "dialog": "Set a fire in our flesh!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce8b3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b4",
      "dialog": "Stay this madness!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce8b4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b5",
      "dialog": "Fire at will!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce8b5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b6",
      "dialog": "You may triumph in the field of battle for a day, but against the power that has risen in the east, there is no victory!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce8b6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b7",
      "dialog": "FIRE!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce8b7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b8",
      "dialog": "NOOOOOO, you will not take my son from me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce8b8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8b9",
      "dialog": "Aaaaaahhhh!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce8b9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ba",
      "dialog": "So passes Denethor, son of Ecthelion.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce8ba"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8bb",
      "dialog": "DEEEEAAATH!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce8bb"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8bc",
      "dialog": "NO! Aaahhh",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce8bc"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8bd",
      "dialog": "Faramir!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce8bd"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8be",
      "dialog": "And who is this? Isildur's heir? It takes more to make a King than a broken Elvish blade.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d5a0844dc4c55e47afef",
      "id": "5cd96e05de30eff6ebcce8be"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8bf",
      "dialog": "I guess that concludes negotiations.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce8bf"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c0",
      "dialog": "In there.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8c0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c1",
      "dialog": "I do not believe it. I will not.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce8c1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c2",
      "dialog": "This army.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce8c2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c3",
      "dialog": "What is this place?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8c3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c4",
      "dialog": "I can't go back.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8c4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c5",
      "dialog": "What's that smell.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8c5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c6",
      "dialog": "Orcses' filth. Orcses come in here sometimes.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8c6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c7",
      "dialog": "Now that I'm here I don't think I want to.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8c7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c8",
      "dialog": "It's the only way. Go in' or go back.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8c8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8c9",
      "dialog": "Hurry! This way.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8c9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ca",
      "dialog": "Smeagol?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8ca"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8cb",
      "dialog": "Over here.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8cb"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8cc",
      "dialog": "Master must go inside the tunnel.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8cc"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8cd",
      "dialog": "You'll see. Oh yes, you will see.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8cd"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ce",
      "dialog": "Re-form the line! Re-form the line!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8ce"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8cf",
      "dialog": "Sound the charge. Take them head-on. Chaaarge!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8cf"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d0",
      "dialog": "Ah aah! Its sticky, what is it?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8d0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d1",
      "dialog": "Take the reins, pull him left. LEFT!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce8d1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d2",
      "dialog": "Make safe the city.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8d2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d3",
      "dialog": "Bring it down! Bring it down! Bring it down!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8d3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d4",
      "dialog": "Merry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce8d4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d5",
      "dialog": "Smeagol? SMEAGOL! SMEAGOL!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8d5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d6",
      "dialog": "Sam.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8d6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d7",
      "dialog": "Ow!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce8d7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d8",
      "dialog": "Cut him down!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce8d8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8d9",
      "dialog": "Aim for the heads!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce8d9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8da",
      "dialog": "Aiya E'rendil Elenion Ancalim'",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8da"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8db",
      "dialog": "Naughty little fly. Why does he cry? Caught in a web. Soon you'll be eaten.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8db"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8dc",
      "dialog": "Drive them to the river.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce8dc"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8dd",
      "dialog": "It wasn't us. It wasn't us. Smeagol wouldn't hurt master. We promised. You must believe us. It was the precious. The precious made us do it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8dd"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8de",
      "dialog": "I have to destroy it Smeagol. I have to destroy it for both our sakes.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8de"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8df",
      "dialog": "NO! Aaaaaaaaa.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8df"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e0",
      "dialog": "And you Frodo Baggins, I give you the light of E'rendil, our most beloved star. May it be a light for you in dark places, when all other lights go out.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd06",
      "id": "5cd96e05de30eff6ebcce8e0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e1",
      "dialog": "I'm so sorry Sam. I'm so sorry.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8e1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e2",
      "dialog": "NO!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce8e2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e3",
      "dialog": "One that is cursed. Long ago the men of the mountains swore an oath to the last King of Gondor, to come to his aid, to fight. But when the time came, when Gondor's need was dire, they fled vanishing into the darkness of the mountain. And so Isildur cursed them, never to rest until they had fulfilled their pledge. Who shall call them from the grey twilight, the forgotten people? The heir of him to whom the oath they swore. From the North shall he come, need shall drive him. He shall pass the door to the Paths of the Dead.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebcce8e3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e4",
      "dialog": "Got away did it precious? Not this time. Not this time.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce8e4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e5",
      "dialog": "What kind of army would linger in such a place?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce8e5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e6",
      "dialog": "The very warmth of my blood seems stolen away.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce8e6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e7",
      "dialog": "The way is shut. It was made by those who are dead, and the dead keep it. The way is shut.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebcce8e7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e8",
      "dialog": "Brego!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce8e8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8e9",
      "dialog": "I do not fear death!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce8e9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ea",
      "dialog": "The scouts report Minas Tirith is surrounded. The lower level's in flames. Everywhere, legions of the enemy advance.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce8ea"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8eb",
      "dialog": "This task was appointed to you, Frodo of the Shire. If you do not find a way, no one will.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd06",
      "id": "5cd96e05de30eff6ebcce8eb"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ec",
      "dialog": "Time is against us. Make ready!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8ec"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ed",
      "dialog": "Take heart Merry. It will soon be over.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce8ed"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ee",
      "dialog": "My lady. You are fair and brave and have much to live for, and many who love you. I know it is too late to turn aside. I know there is not much point now in hoping. If I were a knight of Rohan capable of great deeds'but I'm not. I'm a Hobbit. And I know I can't save Middle Earth. I just want to help my friends; Frodo, Sam, Pippin. More than anything I wish I could see them again.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce8ee"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ef",
      "dialog": "Make haste. We ride through the night.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8ef"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f0",
      "dialog": "Back to the gate! Hurry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce8f0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f1",
      "dialog": "To battle!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce8f1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f2",
      "dialog": "Well this is a thing unheard of. An elf will go underground, where a dwarf dare not. Oh. Oh, I'd never hear the end of it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce8f2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f3",
      "dialog": "Prepare to move out!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce8f3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f4",
      "dialog": "All my friends have gone to battle. I would be ashamed to be left behind.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce8f4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f5",
      "dialog": "It is a three-day gallop to Minas Tirith and none of my riders can bear you as a burdon.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8f5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f6",
      "dialog": "I want to fight!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce8f6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f7",
      "dialog": "I will say no more.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8f7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f8",
      "dialog": "Ride with me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce8f8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8f9",
      "dialog": "My lady!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce8f9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8fa",
      "dialog": "To battle",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce8fa"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8fb",
      "dialog": "We must ride light and swift. It is a long road ahead and man and beast must reach the end with the strength to fight.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8fb"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8fc",
      "dialog": "Ride! Ride now to Gondor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8fc"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8fd",
      "dialog": "What is it? What do you see?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce8fd"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8fe",
      "dialog": "Little Hobbits do not belong in war Master Meriadoc.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce8fe"
    },
    {
      "_id": "5cd96e05de30eff6ebcce8ff",
      "dialog": "Where?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce8ff"
    },
    {
      "_id": "5cd96e05de30eff6ebcce900",
      "dialog": "I see shapes of men and of horses.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebcce900"
    },
    {
      "_id": "5cd96e05de30eff6ebcce901",
      "dialog": "Do not look down.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce901"
    },
    {
      "_id": "5cd96e05de30eff6ebcce902",
      "dialog": "Pale banners like shreds of cloud. Spears rise like winter thickets through a shroud of mist. The dead are following. They have been summoned.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebcce902"
    },
    {
      "_id": "5cd96e05de30eff6ebcce903",
      "dialog": "The dead? Summoned? I knew that! Huh. Huh. Very good. Very good. Legolas!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce903"
    },
    {
      "_id": "5cd96e05de30eff6ebcce904",
      "dialog": "Who enters my domain?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe0d",
      "id": "5cd96e05de30eff6ebcce904"
    },
    {
      "_id": "5cd96e05de30eff6ebcce905",
      "dialog": "One who will have your allegiance.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce905"
    },
    {
      "_id": "5cd96e05de30eff6ebcce906",
      "dialog": "You will suffer me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce906"
    },
    {
      "_id": "5cd96e05de30eff6ebcce907",
      "dialog": "The dead do not suffer the living to pass.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe0d",
      "id": "5cd96e05de30eff6ebcce907"
    },
    {
      "_id": "5cd96e05de30eff6ebcce908",
      "dialog": "The way is shut! It was made by those who are dead. And the dead keep it. (The Ghostly army closes around them) The way is shut! Now you must die!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe0d",
      "id": "5cd96e05de30eff6ebcce908"
    },
    {
      "_id": "5cd96e05de30eff6ebcce909",
      "dialog": "Form up, move out! Form up, move out!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce909"
    },
    {
      "_id": "5cd96e05de30eff6ebcce90a",
      "dialog": "My lord!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce90a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce90b",
      "dialog": "Hail to you sire!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce90b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce90c",
      "dialog": "I bring 500 men from the Westfold my lord.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd32",
      "id": "5cd96e05de30eff6ebcce90c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce90d",
      "dialog": "We have 300 more from Fenmarch, Theoden King.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce90d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce90e",
      "dialog": "That blade was broken!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe0d",
      "id": "5cd96e05de30eff6ebcce90e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce90f",
      "dialog": "It has been remade. Fight for us and regain your honour. What say you? What say you?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce90f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce910",
      "dialog": "None but the King of Gondor may command me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe0d",
      "id": "5cd96e05de30eff6ebcce910"
    },
    {
      "_id": "5cd96e05de30eff6ebcce911",
      "dialog": "I am Isildur's heir. Fight for me and I will hold your oaths fulfilled. What say you?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce911"
    },
    {
      "_id": "5cd96e05de30eff6ebcce912",
      "dialog": "Make way for the King! Make way, the King is here",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce912"
    },
    {
      "_id": "5cd96e05de30eff6ebcce913",
      "dialog": "I summon you to fulfil your oath!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce913"
    },
    {
      "_id": "5cd96e05de30eff6ebcce914",
      "dialog": "Ach! You waste your time Aragorn. They had no honour in life and they have none now in death.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce914"
    },
    {
      "_id": "5cd96e05de30eff6ebcce915",
      "dialog": "Legolas! Run!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce915"
    },
    {
      "_id": "5cd96e05de30eff6ebcce916",
      "dialog": "We fight!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe0d",
      "id": "5cd96e05de30eff6ebcce916"
    },
    {
      "_id": "5cd96e05de30eff6ebcce917",
      "dialog": "Open the gate, quick!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce917"
    },
    {
      "_id": "5cd96e05de30eff6ebcce918",
      "dialog": "Quick! Hurry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d5cf844dc4c55e47aff0",
      "id": "5cd96e05de30eff6ebcce918"
    },
    {
      "_id": "5cd96e05de30eff6ebcce919",
      "dialog": "Faramir! Say not that he has fallen.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce919"
    },
    {
      "_id": "5cd96e05de30eff6ebcce91a",
      "dialog": "They were outnumbered! None survived.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d5cf844dc4c55e47aff0",
      "id": "5cd96e05de30eff6ebcce91a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce91b",
      "dialog": "Stand you traitors!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce91b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce91c",
      "dialog": "Out!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce91c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce91d",
      "dialog": "Where are the riders from Snowbourn?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce91d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce91e",
      "dialog": "None have come my lord.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce91e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce91f",
      "dialog": "Six thousand spears, less than half of what I had hoped for.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce91f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce920",
      "dialog": "You have my word! Fight and I will release you from this living death! What say you?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce920"
    },
    {
      "_id": "5cd96e05de30eff6ebcce921",
      "dialog": "Fear. The city is rank with it! Ha ha ha ha. Let us ease their pain. Release the prisoners!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce921"
    },
    {
      "_id": "5cd96e05de30eff6ebcce922",
      "dialog": "The horses are restless and the men are quiet.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebcce922"
    },
    {
      "_id": "5cd96e05de30eff6ebcce923",
      "dialog": "They grow nervous in the shadow of the mountain.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce923"
    },
    {
      "_id": "5cd96e05de30eff6ebcce924",
      "dialog": "That road there where does that lead?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce924"
    },
    {
      "_id": "5cd96e05de30eff6ebcce925",
      "dialog": "It is the road to the Dimholt, the door under the mountain.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebcce925"
    },
    {
      "_id": "5cd96e05de30eff6ebcce926",
      "dialog": "Catapults! ha ha ha.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce926"
    },
    {
      "_id": "5cd96e05de30eff6ebcce927",
      "dialog": "More will come.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce927"
    },
    {
      "_id": "5cd96e05de30eff6ebcce928",
      "dialog": "My sons are spent! My line has ended!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce928"
    },
    {
      "_id": "5cd96e05de30eff6ebcce929",
      "dialog": "Six thousand will not be enough to break the lines of Mordor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce929"
    },
    {
      "_id": "5cd96e05de30eff6ebcce92a",
      "dialog": "Every hour lost hastens Gondor's defeat. We have until dawn then we must ride.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce92a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce92b",
      "dialog": "My line has ended!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce92b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce92c",
      "dialog": "My lord!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce92c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce92d",
      "dialog": "Rohan has deserted us!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce92d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce92e",
      "dialog": "Theoden's betrayed me! ABANDON YOUR POSTS! FLEE! FLEE FOR YOUR LIVES!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce92e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce92f",
      "dialog": "Prepare for battle. Hurry men! To the wall! Defend the wall! Over here! Return to your posts.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce92f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce930",
      "dialog": "Send these foul beasts into the Abyss.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce930"
    },
    {
      "_id": "5cd96e05de30eff6ebcce931",
      "dialog": "The house of Stewards has failed.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce931"
    },
    {
      "_id": "5cd96e05de30eff6ebcce932",
      "dialog": "We need more rubble!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce932"
    },
    {
      "_id": "5cd96e05de30eff6ebcce933",
      "dialog": "He needs medicine my lord!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce933"
    },
    {
      "_id": "5cd96e05de30eff6ebcce934",
      "dialog": "None who venture there ever return. That mountain is evil.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce934"
    },
    {
      "_id": "5cd96e05de30eff6ebcce935",
      "dialog": "Aragorn! Let's find some food.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce935"
    },
    {
      "_id": "5cd96e05de30eff6ebcce936",
      "dialog": "There. A true esquire of Rohan.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce936"
    },
    {
      "_id": "5cd96e05de30eff6ebcce937",
      "dialog": "I'm ready! Sorry. It isn't all that dangerous. It's not even sharp.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebcce937"
    },
    {
      "_id": "5cd96e05de30eff6ebcce938",
      "dialog": "He's alive!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce938"
    },
    {
      "_id": "5cd96e05de30eff6ebcce939",
      "dialog": "Stay where you are!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce939"
    },
    {
      "_id": "5cd96e05de30eff6ebcce93a",
      "dialog": "To the smithy, go!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce93a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce93b",
      "dialog": "You should not encourage him.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce93b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce93c",
      "dialog": "You should not doubt him.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce93c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce93d",
      "dialog": "Sir? King Theoden awaits you my lord.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce93d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce93e",
      "dialog": "Watch out!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce93e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce93f",
      "dialog": "Down to the lower levels quick!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce93f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce940",
      "dialog": "I do not doubt his heart, only the reach of his arm.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce940"
    },
    {
      "_id": "5cd96e05de30eff6ebcce941",
      "dialog": "Why should Merry be left behind? He has as much cause to go to war as you. Why can he not fight for those he loves?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce941"
    },
    {
      "_id": "5cd96e05de30eff6ebcce942",
      "dialog": "Double up men!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce942"
    },
    {
      "_id": "5cd96e05de30eff6ebcce943",
      "dialog": "Hold them back, do not give in to fear. Stand to your posts. Fight!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce943"
    },
    {
      "_id": "5cd96e05de30eff6ebcce944",
      "dialog": "Not at the towers! Aim for the trolls, kill the trolls!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce944"
    },
    {
      "_id": "5cd96e05de30eff6ebcce945",
      "dialog": "You know as little of war as that Hobbit. When the fear takes him, and the blood and the screams and the horror of battle take hold. Do you think he would stand and fight? He would flee. And he would be right to do so. War is the province of men Eowyn.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcce945"
    },
    {
      "_id": "5cd96e05de30eff6ebcce946",
      "dialog": "Bring them down!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce946"
    },
    {
      "_id": "5cd96e05de30eff6ebcce947",
      "dialog": "They called us out to fight.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce947"
    },
    {
      "_id": "5cd96e05de30eff6ebcce948",
      "dialog": "Fight them back!Peregrin Took! Go back to the Citadel.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce948"
    },
    {
      "_id": "5cd96e05de30eff6ebcce949",
      "dialog": "This is no place for a Hobbit!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce949"
    },
    {
      "_id": "5cd96e05de30eff6ebcce94a",
      "dialog": "What are you doing you useless scum?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce94a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce94b",
      "dialog": "My lord Elrond",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce94b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce94c",
      "dialog": "Guard of the Citadel indeed! Now back up the hill quickly. Quick!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce94c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce94d",
      "dialog": "The door wont give. It's too strong.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce94d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce94e",
      "dialog": "I come on behalf of one whom I love. Arwen is dying. She will not long survive the evil that now spreads from Mordor. The light of the evenstar is failing. As Sauron's power grows her strength wanes. Arwen's life is now tied to the fate of the Ring. The Shadow is upon us Aragorn. The end has come.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebcce94e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce94f",
      "dialog": "There are none.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce94f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce950",
      "dialog": "There are those that dwell in the mountain.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebcce950"
    },
    {
      "_id": "5cd96e05de30eff6ebcce951",
      "dialog": "Murderers, traitors. You would call upon them to fight? They believe in nothing. They answer to no one",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce951"
    },
    {
      "_id": "5cd96e05de30eff6ebcce952",
      "dialog": "I take my leave.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce952"
    },
    {
      "_id": "5cd96e05de30eff6ebcce953",
      "dialog": "Sauron will not have forgotten the sword of Elendil.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce953"
    },
    {
      "_id": "5cd96e05de30eff6ebcce954",
      "dialog": "You ride to war but not to victory. Sauron's armies ride on Minas Tirith, this you know. But in secret he sends another force, which will attack, from the river. A fleet of Corsair ships sails from the South. They will be in the city in two days. You're outnumbered Aragorn. You need more men.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebcce954"
    },
    {
      "_id": "5cd96e05de30eff6ebcce955",
      "dialog": "It will not be our end, but his.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce955"
    },
    {
      "_id": "5cd96e05de30eff6ebcce956",
      "dialog": "They will answer to the King of Gondor. And'ril, the Flame of the West, forged from the shards of Narsil.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebcce956"
    },
    {
      "_id": "5cd96e05de30eff6ebcce957",
      "dialog": "The blade that was broken shall return to Minas Tirith.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce957"
    },
    {
      "_id": "5cd96e05de30eff6ebcce958",
      "dialog": "The man who can wield the power of this sword can summon to him an army more deadly than any that walks this earth. Put aside the Ranger. Become who you were born to be 'nen i-Estel Edain.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebcce958"
    },
    {
      "_id": "5cd96e05de30eff6ebcce959",
      "dialog": "'-chebin Estel anim.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce959"
    },
    {
      "_id": "5cd96e05de30eff6ebcce95a",
      "dialog": "I didn't think they would find any livery that would fit me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce95a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce95b",
      "dialog": "It once belonged to a young boy of the city. A very foolish one who wasted many hours slaying dragons instead of attending his studies.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce95b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce95c",
      "dialog": "This was yours?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce95c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce95d",
      "dialog": "Yes, it was mine. My father had it made for me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce95d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce95e",
      "dialog": "Get back there and smash it down!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce95e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce95f",
      "dialog": "But nothing can breach it!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce95f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce960",
      "dialog": "It was well done. A generous deed should not be checked with cold counsel. You are to join the tower guard.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce960"
    },
    {
      "_id": "5cd96e05de30eff6ebcce961",
      "dialog": "What were you thinking Peregrin Took? What service can a Hobbit offer such a great lord of men?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce961"
    },
    {
      "_id": "5cd96e05de30eff6ebcce962",
      "dialog": "Grond, Grond, Grond, Grond, Grond!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce962"
    },
    {
      "_id": "5cd96e05de30eff6ebcce963",
      "dialog": "Grond, Grond, Grond, Grond!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce963"
    },
    {
      "_id": "5cd96e05de30eff6ebcce964",
      "dialog": "Eowyn!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce964"
    },
    {
      "_id": "5cd96e05de30eff6ebcce965",
      "dialog": "Why are you doing this? The war lies to the East. You cannot leave on the eve of battle. You cannot abandon the men.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce965"
    },
    {
      "_id": "5cd96e05de30eff6ebcce966",
      "dialog": "Grond will breach it! Bring out the wolf's head.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce966"
    },
    {
      "_id": "5cd96e05de30eff6ebcce967",
      "dialog": "We need you here.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce967"
    },
    {
      "_id": "5cd96e05de30eff6ebcce968",
      "dialog": "I have wished you joy since first I saw you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce968"
    },
    {
      "_id": "5cd96e05de30eff6ebcce969",
      "dialog": "Just where do you think you're off to?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce969"
    },
    {
      "_id": "5cd96e05de30eff6ebcce96a",
      "dialog": "Not this time. This time you must stay, Gimli.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce96a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce96b",
      "dialog": "Hmmmm",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce96b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce96c",
      "dialog": "Have you learnt nothing of the stubbornness of dwarves?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebcce96c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce96d",
      "dialog": "You might as well accept it. We're going with you laddie. Aragorn smiles.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcce96d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce96e",
      "dialog": "Do you not know?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebcce96e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce96f",
      "dialog": "It is but a shadow and a thought that you love. I cannot give you what you seek.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce96f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce970",
      "dialog": "He leaves because there is no hope.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0e",
      "id": "5cd96e05de30eff6ebcce970"
    },
    {
      "_id": "5cd96e05de30eff6ebcce971",
      "dialog": "He leaves because he must.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce971"
    },
    {
      "_id": "5cd96e05de30eff6ebcce972",
      "dialog": "Well, I'm taller than you were then. Though, I'm not likely to grow anymore, except sideways.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce972"
    },
    {
      "_id": "5cd96e05de30eff6ebcce973",
      "dialog": "Why have you come?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcce973"
    },
    {
      "_id": "5cd96e05de30eff6ebcce974",
      "dialog": "What's happening, where is he going? I don't understand. Lord Aragorn! Why does he leave on the eve of battle?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce974"
    },
    {
      "_id": "5cd96e05de30eff6ebcce975",
      "dialog": "It never fitted me either. Boromir was always the soldier. They were so alike he and my father. Proud, stubborn even, but strong.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce975"
    },
    {
      "_id": "5cd96e05de30eff6ebcce976",
      "dialog": "I think you have strength of a different kind. And one day your father will see it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce976"
    },
    {
      "_id": "5cd96e05de30eff6ebcce977",
      "dialog": "And I shall not forget it! nor fail to reward that which is given. Fealty with love. Valour with honour. Disloyalty with vengeance. I do not think we should so lightly abandon the outer defences. Defences that your brother long held intact.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce977"
    },
    {
      "_id": "5cd96e05de30eff6ebcce978",
      "dialog": "What would you have me do?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce978"
    },
    {
      "_id": "5cd96e05de30eff6ebcce979",
      "dialog": "I will not yield the River and Pellenor unfought. Osgiliath must be retaken.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce979"
    },
    {
      "_id": "5cd96e05de30eff6ebcce97a",
      "dialog": "My lord, Osgiliath is over run.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce97a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce97b",
      "dialog": "Much must be risked in war. Is there a Captain here who still has the courage to do his lord's will?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce97b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce97c",
      "dialog": "You wish now that our places had been exchanged. That I had died and Boromir had lived.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce97c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce97d",
      "dialog": "Here do I swear fealty and service to Gondor in peace or war, in living or dying, from, ' from this hour henceforth until my lord release me or death take me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce97d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce97e",
      "dialog": "No, we cannot. But we will meet them in battle nonetheless.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce97e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce97f",
      "dialog": "I have left instruction. The people are to follow your rule in my stead. Take up my seat in the Golden Hall. Long may you defend Edoras, if the battle goes ill.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce97f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce980",
      "dialog": "What other duty would you have me do my lord?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce980"
    },
    {
      "_id": "5cd96e05de30eff6ebcce981",
      "dialog": "Duty? No. I would have you smile again, not grieve for those whose time has come. You shall live to see these days renewed, ' and no more despair",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcce981"
    },
    {
      "_id": "5cd96e05de30eff6ebcce982",
      "dialog": "Yes, I wish that.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce982"
    },
    {
      "_id": "5cd96e05de30eff6ebcce983",
      "dialog": "Since you are robbed of Boromir I will do what I can in his stead. If I should return, think better of me father.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce983"
    },
    {
      "_id": "5cd96e05de30eff6ebcce984",
      "dialog": "To few have come. We cannot defeat the armies of Mordor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0e",
      "id": "5cd96e05de30eff6ebcce984"
    },
    {
      "_id": "5cd96e05de30eff6ebcce985",
      "dialog": "Sneaking? Sneaking? Fat Hobbit is always so polite. Smeagol shows them secret ways that nobody else could find and they say 'sneak!' Sneak? Very nice friend, oh yes my precious very nice, very nice!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce985"
    },
    {
      "_id": "5cd96e05de30eff6ebcce986",
      "dialog": "Alright! Alright! You just startled me is all. What were you doing?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce986"
    },
    {
      "_id": "5cd96e05de30eff6ebcce987",
      "dialog": "Sneaking.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce987"
    },
    {
      "_id": "5cd96e05de30eff6ebcce988",
      "dialog": "Fine, have it your own way. I'm sorry to wake you Mr Frodo but we have to be moving on.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce988"
    },
    {
      "_id": "5cd96e05de30eff6ebcce989",
      "dialog": "It's dark still.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce989"
    },
    {
      "_id": "5cd96e05de30eff6ebcce98a",
      "dialog": "It's always dark here. It's gone! The elven bread!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce98a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce98b",
      "dialog": "Ech!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce98b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce98c",
      "dialog": "What? That's all we have left!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce98c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce98d",
      "dialog": "We can't hold them. The city is lost.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdf477ed9587226e7949b",
      "id": "5cd96e05de30eff6ebcce98d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce98e",
      "dialog": "What are you up to? Sneaking off are we?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce98e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce98f",
      "dialog": "That will depend on the manner of your return.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce98f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce990",
      "dialog": "He took it. He must have.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce990"
    },
    {
      "_id": "5cd96e05de30eff6ebcce991",
      "dialog": "Smeagol? No, no, not poor Smeagol. Smeagol hates nasty elf bread.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce991"
    },
    {
      "_id": "5cd96e05de30eff6ebcce992",
      "dialog": "You're a lying rat! What did you do with it?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce992"
    },
    {
      "_id": "5cd96e05de30eff6ebcce993",
      "dialog": "He doesn't eat it. He can't have taken it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce993"
    },
    {
      "_id": "5cd96e05de30eff6ebcce994",
      "dialog": "Look, what's this? Crumbs on his jacketses. He took it! He took it! I've seen him, he's always stuffing his face when master's not looking.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce994"
    },
    {
      "_id": "5cd96e05de30eff6ebcce995",
      "dialog": "That's a filthy lie! You stinking, two faced sneak!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce995"
    },
    {
      "_id": "5cd96e05de30eff6ebcce996",
      "dialog": "Tell the men to break cover. We ride for Minas Tirith.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce996"
    },
    {
      "_id": "5cd96e05de30eff6ebcce997",
      "dialog": "Nazg'l!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc95",
      "id": "5cd96e05de30eff6ebcce997"
    },
    {
      "_id": "5cd96e05de30eff6ebcce998",
      "dialog": "Take cover! Nazgul! Fall back. Fall back to Minas Tirith!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce998"
    },
    {
      "_id": "5cd96e05de30eff6ebcce999",
      "dialog": "Stop it!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce999"
    },
    {
      "_id": "5cd96e05de30eff6ebcce99a",
      "dialog": "I'll kill him!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce99a"
    },
    {
      "_id": "5cd96e05de30eff6ebcce99b",
      "dialog": "Call me'",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce99b"
    },
    {
      "_id": "5cd96e05de30eff6ebcce99c",
      "dialog": "Sam, no!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce99c"
    },
    {
      "_id": "5cd96e05de30eff6ebcce99d",
      "dialog": "No. No you're not all right, you're exhausted. It's that Gollum. It's this place. It's that thing around your neck. I could help a bit. I could carry it for a while, carry it for a while, I could carry it! I could carry it! Share the load! Share the load! Share the load!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce99d"
    },
    {
      "_id": "5cd96e05de30eff6ebcce99e",
      "dialog": "Get away!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce99e"
    },
    {
      "_id": "5cd96e05de30eff6ebcce99f",
      "dialog": "Fall back! Retreat! Retreat! Run for your lives!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce99f"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a0",
      "dialog": "The age of men is over. The time of the Orc has come.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcce9a0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a1",
      "dialog": "I'm all right.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce9a1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a2",
      "dialog": "Oh my! I'm sorry. I didn't mean it to go so far. I was just so, so angry! Here just' let's just rest a bit.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce9a2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a3",
      "dialog": "Keep going. It's the Nazgul. Take cover my lord. It's coming.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce9a3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a4",
      "dialog": "Sam!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce9a4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a5",
      "dialog": "It's Mithrandir! The White Rider!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce9a5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a6",
      "dialog": "Foreseen and done nothing!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce9a6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a7",
      "dialog": "Faramir? This is not the first Halfling to have crossed your path.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce9a7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a8",
      "dialog": "Pull!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce9a8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9a9",
      "dialog": "Mithrandir! They broke through our defences. They've taken the bridge and the West bank. Battalions of Orcs are crossing the river.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9a9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9aa",
      "dialog": "It is as the Lord Denethor predicted! Long has he foreseen this doom!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d5cf844dc4c55e47aff0",
      "id": "5cd96e05de30eff6ebcce9aa"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9ab",
      "dialog": "You've seen Frodo and Sam?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce9ab"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9ac",
      "dialog": "No.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9ac"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9ad",
      "dialog": "Where? When?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce9ad"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9ae",
      "dialog": "I don't want to keep it. I just want to help.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce9ae"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9af",
      "dialog": "See? See? He wants it for himself.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce9af"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9b0",
      "dialog": "Shut up you! Go away! Get out of here!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce9b0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9b1",
      "dialog": "No Sam! It's you! I'm sorry Sam.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce9b1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9b2",
      "dialog": "But he's a liar! He's poisoned you against me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce9b2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9b3",
      "dialog": "You can't help me any more.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce9b3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9b4",
      "dialog": "You don't mean that.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce9b4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9b5",
      "dialog": "Go home.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcce9b5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9b6",
      "dialog": "Can you sing, Master Hobbit?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce9b6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9b7",
      "dialog": "Well, yes. At least well enough for my own people. But we have no songs for great halls and evil times.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce9b7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9bb",
      "dialog": "In Ithilien. Not two days ago. Gandalf, they're taking the road to the Morgul vale.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9bb"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9bc",
      "dialog": "Where does my allegiance lie if not here? This is the city of the men of N'menor. I will gladly give my life to defend her beauty, her memory, her wisdom.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9bc"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9bd",
      "dialog": "What does that mean? What's wrong? He looks at Gandalf.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce9bd"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9be",
      "dialog": "Faramir! Faramir! Your father's will has turned to madness. Do not throw away your life so rashly.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce9be"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9bf",
      "dialog": "Your father loves you Faramir. He will remember it before the end.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce9bf"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c0",
      "dialog": "And then the pass of Cirith Ungol.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce9c0"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c1",
      "dialog": "What you judged to be right! You sent the Ring of power into Mordor in the hands of a witless Halfling! It should have been brought back to the citadel to be kept safe. Hidden. Dark and deep in the vaults' not to be used. unless, at the uttermost end of need.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce9c1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c2",
      "dialog": "I would not use the Ring. Not if Minas Tirith were falling in ruin and I alone could save her.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9c2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c3",
      "dialog": "Ever you desire to appear lordly and gracious as a King of old. Boromir would have remembered his father's need. He would have brought me a kingly gift",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce9c3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c4",
      "dialog": "Boromir would not have brought the Ring. He would have stretched out his hand to this thing and taking it he would have fallen.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9c4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c5",
      "dialog": "This is how you would serve your city? You would risk its utter ruin?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce9c5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c6",
      "dialog": "I did what I judged to be right.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9c6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c7",
      "dialog": "And why should your songs be unfit for my halls? Come, sing me a song.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce9c7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c8",
      "dialog": "Home is behind, The world ahead, And there are many paths to tread, Through shadow, to the edge of night, Until the stars are all alight. Mist and shadow cloud and shade, All shall fade, All shall, 'fade.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcce9c8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9c9",
      "dialog": "Faramir tell me everything. Tell me all you know.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce9c9"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9ca",
      "dialog": "March, march! March, march march!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce9ca"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9d8",
      "dialog": "You know nothing of this matter!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce9d8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9da",
      "dialog": "Father?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9da"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9db",
      "dialog": "My son! Leave me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce9db"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9dc",
      "dialog": "Careful master! Careful. Very far to fall. Very dangerous are the stairs.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce9dc"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9dd",
      "dialog": "Come master.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce9dd"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9de",
      "dialog": "Come to Smeagol.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce9de"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9df",
      "dialog": "Mr Frodo! Get back you! Don't touch him.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcce9df"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9e1",
      "dialog": "He would have kept it for his own. And when he returned you would not have known your son.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcce9e1"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9e2",
      "dialog": "Send forth all legions. Do not stop the attack until the city is taken.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d576844dc4c55e47afee",
      "id": "5cd96e05de30eff6ebcce9e2"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9e3",
      "dialog": "Boromir was loyal to me! Not some wizard's pupil.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcce9e3"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9e4",
      "dialog": "Why does he hates poor Smeagol? What has Smeagol ever done to him? Master? Master carries a heavy burden. Smeagol knows, heavy heavy burden. Fat one cannot know. He wants it. He needs it. Smeagol sees it in his eye. Very soon he will ask you for it. You will see. The fat one will take it from you!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcce9e4"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9f5",
      "dialog": "I will break him.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d576844dc4c55e47afee",
      "id": "5cd96e05de30eff6ebcce9f5"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9f6",
      "dialog": "Where are Theoden's riders?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce9f6"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9f7",
      "dialog": "Will Rohan's army come? Mithrandir?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcce9f7"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9f8",
      "dialog": "Courage is the best defence that you have now.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcce9f8"
    },
    {
      "_id": "5cd96e05de30eff6ebcce9fb",
      "dialog": "Slay them all!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd9d576844dc4c55e47afee",
      "id": "5cd96e05de30eff6ebcce9fb"
    },
    {
      "_id": "5cd96e05de30eff6ebccea01",
      "dialog": "What of the wizard?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebccea01"
    },
    {
      "_id": "5cd96e05de30eff6ebccebe1",
      "dialog": "Pull back! Pull back!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccebe1"
    },
    {
      "_id": "5cd96e05de30eff6ebccebe2",
      "dialog": "Sons of Gondor, of Rohan, my brothers. I see it in your eyes, the same fear that would take the heart of me. A day may come when the courage of men fails, when we forsake our friends and break all bonds of fellowship, but it is not this day! An hour of wolves and shattered shields when the age of men comes crashing down, but it is not this day! This day we fight!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccebe2"
    },
    {
      "_id": "5cd96e05de30eff6ebccebe3",
      "dialog": "By all that you hold dear on this good earth, I bid you stand! Men of the West!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccebe3"
    },
    {
      "_id": "5cd96e05de30eff6ebccebe4",
      "dialog": "It's gone Mr Frodo. The light's passed on, away towards the North. Something's drawn its gaze.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccebe4"
    },
    {
      "_id": "5cd96e05de30eff6ebccebe6",
      "dialog": "Hold your ground! Hold your ground!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccebe6"
    },
    {
      "_id": "5cd96e05de30eff6ebccebe7",
      "dialog": "Never thought I'd die fighting side by side with an elf.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccebe7"
    },
    {
      "_id": "5cd96e05de30eff6ebccec08",
      "dialog": "What about side by side with a friend?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccec08"
    },
    {
      "_id": "5cd96e05de30eff6ebccec09",
      "dialog": "Do you remember the Shire Mr Frodo? It will be Spring soon and the orchards will be in blossom. And the birds will be nesting in the hazel thickets. (He is crying.) And they will be sowing the summer barley in the lower fields, (Frodo opens his eyes and looks at him.) and eating the first of the strawberries and cream. Do you remember the taste of strawberries?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec09"
    },
    {
      "_id": "5cd96e05de30eff6ebccec0a",
      "dialog": "No Sam. I can't recall the taste of food, nor the sound of water or the touch of grass. I'm naked in the dark. There's' there's nothing, no veil between me and the wheel of fire. I can see him with my waking eyes!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccec0a"
    },
    {
      "_id": "5cd96e05de30eff6ebccec0b",
      "dialog": "Then let us be rid of it once and for all! Come on Mr Frodo, I can't carry it for you, but I can carry you! Come on!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec0b"
    },
    {
      "_id": "5cd96e05de30eff6ebccec0c",
      "dialog": "Aragorn! Elessar!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea5",
      "id": "5cd96e05de30eff6ebccec0c"
    },
    {
      "_id": "5cd96e05de30eff6ebccec0d",
      "dialog": "For Frodo.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccec0d"
    },
    {
      "_id": "5cd96e05de30eff6ebccec0e",
      "dialog": "Look Mr Frodo, a doorway! We're almost there!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec0e"
    },
    {
      "_id": "5cd96e05de30eff6ebccec0f",
      "dialog": "Aye! I could do that.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccec0f"
    },
    {
      "_id": "5cd96e05de30eff6ebccec10",
      "dialog": "Clever Hobbits to climb so high! Mustn't go that way. Mustn't hurt the precious!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccec10"
    },
    {
      "_id": "5cd96e05de30eff6ebccec19",
      "dialog": "You swore! You swore on the precious!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccec19"
    },
    {
      "_id": "5cd96e05de30eff6ebccec38",
      "dialog": "The eagles! The eagles are coming!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccec38"
    },
    {
      "_id": "5cd96e05de30eff6ebccec3a",
      "dialog": "Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec3a"
    },
    {
      "_id": "5cd96e05de30eff6ebccec3b",
      "dialog": "I'm here Sam!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccec3b"
    },
    {
      "_id": "5cd96e05de30eff6ebccec3d",
      "dialog": "Destroy it!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec3d"
    },
    {
      "_id": "5cd96e05de30eff6ebccec3e",
      "dialog": "The Ring is mine!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccec3e"
    },
    {
      "_id": "5cd96e05de30eff6ebccec3f",
      "dialog": "What are you waiting for? Just let it go!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec3f"
    },
    {
      "_id": "5cd96e05de30eff6ebccec40",
      "dialog": "Nooooooo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec40"
    },
    {
      "_id": "5cd96e05de30eff6ebccec42",
      "dialog": "Yeees! Yeees! Precious! My Precious!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccec42"
    },
    {
      "_id": "5cd96e05de30eff6ebccec45",
      "dialog": "Go on! Now! Throw it in the fire!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec45"
    },
    {
      "_id": "5cd96e05de30eff6ebccec46",
      "dialog": "No!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec46"
    },
    {
      "_id": "5cd96e05de30eff6ebccec4d",
      "dialog": "Fifteen, sixteen.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccec4d"
    },
    {
      "_id": "5cd96e05de30eff6ebccec4f",
      "dialog": "Legolas!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccec4f"
    },
    {
      "_id": "5cd96e05de30eff6ebccec50",
      "dialog": "Thirty three, thirty four.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccec50"
    },
    {
      "_id": "5cd96e05de30eff6ebccec52",
      "dialog": "Merry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebccec52"
    },
    {
      "_id": "5cd96e05de30eff6ebccec53",
      "dialog": "No, no. I'm going to save you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebccec53"
    },
    {
      "_id": "5cd96e05de30eff6ebccec54",
      "dialog": "Come on then, come on!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebccec54"
    },
    {
      "_id": "5cd96e05de30eff6ebccec55",
      "dialog": "You already did. Eowyn, my body is broken. You have to let me go.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccec55"
    },
    {
      "_id": "5cd96e05de30eff6ebccec56",
      "dialog": "Smeagol promised!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccec56"
    },
    {
      "_id": "5cd96e05de30eff6ebccec57",
      "dialog": "Smeagol lied!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccec57"
    },
    {
      "_id": "5cd96e05de30eff6ebccec58",
      "dialog": "AAAAAAAAAhhhhhhhhhh!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec58"
    },
    {
      "_id": "5cd96e05de30eff6ebccec59",
      "dialog": "AAAAAHH",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccec59"
    },
    {
      "_id": "5cd96e05de30eff6ebccec5a",
      "dialog": "That still only counts as one!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccec5a"
    },
    {
      "_id": "5cd96e05de30eff6ebccec5b",
      "dialog": "I know your face, Eowyn. My eyes darken.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccec5b"
    },
    {
      "_id": "5cd96e05de30eff6ebccec5c",
      "dialog": "Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec5c"
    },
    {
      "_id": "5cd96e05de30eff6ebccec6b",
      "dialog": "I knew you'd find me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccec6b"
    },
    {
      "_id": "5cd96e05de30eff6ebccec6c",
      "dialog": "Merry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccec6c"
    },
    {
      "_id": "5cd96e05de30eff6ebccec6e",
      "dialog": "Yes.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccec6e"
    },
    {
      "_id": "5cd96e05de30eff6ebccec6f",
      "dialog": "Are you going to leave me?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccec6f"
    },
    {
      "_id": "5cd96e05de30eff6ebccec70",
      "dialog": "No Merry, I'm going to look after you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccec70"
    },
    {
      "_id": "5cd96e05de30eff6ebccec72",
      "dialog": "Hands off! That shiny shirt, that's mine!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa9b",
      "id": "5cd96e05de30eff6ebccec72"
    },
    {
      "_id": "5cd96e05de30eff6ebccec73",
      "dialog": "Merry! Merry it's me. It's Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccec73"
    },
    {
      "_id": "5cd96e05de30eff6ebccec91",
      "dialog": "Give me your hand.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec91"
    },
    {
      "_id": "5cd96e05de30eff6ebccec92",
      "dialog": "Frodo.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccec92"
    },
    {
      "_id": "5cd96e05de30eff6ebccec93",
      "dialog": "It's gone. It's done.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccec93"
    },
    {
      "_id": "5cd96e05de30eff6ebccec94",
      "dialog": "Yes Mr Frodo. It's over now.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec94"
    },
    {
      "_id": "5cd96e05de30eff6ebccec95",
      "dialog": "I can see the Shire. The Brandywine River. Bag End. Gandalf's fireworks. The lights on the party tree.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccec95"
    },
    {
      "_id": "5cd96e05de30eff6ebccec96",
      "dialog": "Rosie Cotton dancing. She had ribbons in her hair. If ever I was to marry someone, it would have been her. It would've been her.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec96"
    },
    {
      "_id": "5cd96e05de30eff6ebccec97",
      "dialog": "I'm glad to be with you Samwise Gamgee here at the end of all things. They hug.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccec97"
    },
    {
      "_id": "5cd96e05de30eff6ebccec98",
      "dialog": "Take my hand.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec98"
    },
    {
      "_id": "5cd96e05de30eff6ebccec99",
      "dialog": "No! Don't you let go! Don't let go! Reeeaaach!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec99"
    },
    {
      "_id": "5cd96e05de30eff6ebccec9a",
      "dialog": "Frodo!Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccec9a"
    },
    {
      "_id": "5cd96e05de30eff6ebccec9b",
      "dialog": "Gondor is lost. There is no hope for men. Why do the fools fly? Better to die sooner than late. For die we must.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebccec9b"
    },
    {
      "_id": "5cd96e05de30eff6ebccec9c",
      "dialog": "No tomb for Denethor and Faramir. No long slow sleep of death embalmed. We shall burn like the heathen Kings of old. Bring wood and oil.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebccec9c"
    },
    {
      "_id": "5cd96e05de30eff6ebccec9d",
      "dialog": "I am steward of the house of An'rion. Thus have I walked, and thus now I will sleep.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebccec9d"
    },
    {
      "_id": "5cd96e05de30eff6ebccec9e",
      "dialog": "Let him go, you filth! Let him go!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec9e"
    },
    {
      "_id": "5cd96e05de30eff6ebccec9f",
      "dialog": "You will not touch him again! Come on then, finish it!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccec9f"
    },
    {
      "_id": "5cd96e05de30eff6ebcceca2",
      "dialog": "You are soldiers of Gondor. No matter what comes through that gate you will stand your ground.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcceca2"
    },
    {
      "_id": "5cd96e05de30eff6ebcceca3",
      "dialog": "Steady! Steady!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcceca3"
    },
    {
      "_id": "5cd96e05de30eff6ebcceca6",
      "dialog": "Volley! Fire!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcceca6"
    },
    {
      "_id": "5cd96e05de30eff6ebccecab",
      "dialog": "Peregrin Took my lad, there is a task now to be done. Another opportunity for one of the Shire folk to prove their great worth. You must not fail me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccecab"
    },
    {
      "_id": "5cd96e05de30eff6ebccecac",
      "dialog": "It's been very quiet across the river.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebccecac"
    },
    {
      "_id": "5cd96e05de30eff6ebccecad",
      "dialog": "The Orcs are lying low. The garrison may have moved out. We've sent scouts to Cair Andros. If the Orcs attack from the North, we'll have some warning.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdf477ed9587226e7949b",
      "id": "5cd96e05de30eff6ebccecad"
    },
    {
      "_id": "5cd96e05de30eff6ebccecae",
      "dialog": "No.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebccecae"
    },
    {
      "_id": "5cd96e05de30eff6ebccecaf",
      "dialog": "We need 10 more.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebccecaf"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb0",
      "dialog": "Quiet.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebccecb0"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb1",
      "dialog": "Bad idea! Very handy in a tight spot these lads, despite the fact they're dead.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccecb1"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb2",
      "dialog": "You gave us your word!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe0d",
      "id": "5cd96e05de30eff6ebccecb2"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb3",
      "dialog": "I hold your oath fulfilled. Go. Be at peace.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccecb3"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb4",
      "dialog": "Merry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccecb4"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb5",
      "dialog": "Nooooo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebccecb5"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb6",
      "dialog": "Nooooooo! Noooooo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebccecb6"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb7",
      "dialog": "Eowyn.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccecb7"
    },
    {
      "_id": "5cd96e05de30eff6ebccecb8",
      "dialog": "Release us!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe0d",
      "id": "5cd96e05de30eff6ebccecb8"
    },
    {
      "_id": "5cd96e05de30eff6ebccecbe",
      "dialog": "I go to my fathers, in whose mighty company; I shall not now feel ashamed.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccecbe"
    },
    {
      "_id": "5cd96e05de30eff6ebccecc8",
      "dialog": "I don't take orders from stinking Morgul-rats!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa9b",
      "id": "5cd96e05de30eff6ebccecc8"
    },
    {
      "_id": "5cd96e05de30eff6ebccecc9",
      "dialog": "You touch it and I'll stick this blade in your gut!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebccecc9"
    },
    {
      "_id": "5cd96e05de30eff6ebccecca",
      "dialog": "The scum tried to knife me. Kill him!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa9b",
      "id": "5cd96e05de30eff6ebccecca"
    },
    {
      "_id": "5cd96e05de30eff6ebcceccb",
      "dialog": "That's for Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcceccb"
    },
    {
      "_id": "5cd96e05de30eff6ebcceccc",
      "dialog": "It's going to the Great Eye, along with everything else.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebcceccc"
    },
    {
      "_id": "5cd96e05de30eff6ebccecce",
      "dialog": "And the Shire!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccecce"
    },
    {
      "_id": "5cd96e05de30eff6ebcceccf",
      "dialog": "Stop your squealing you dunghill rat!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebcceccf"
    },
    {
      "_id": "5cd96e05de30eff6ebccecd0",
      "dialog": "I'm gonna bleed you like a stuck pig!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebccecd0"
    },
    {
      "_id": "5cd96e05de30eff6ebccecd1",
      "dialog": "Not if I stick you first!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccecd1"
    },
    {
      "_id": "5cd96e05de30eff6ebccecd2",
      "dialog": "Sam!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccecd2"
    },
    {
      "_id": "5cd96e05de30eff6ebccecd3",
      "dialog": "Oh Sam, I'm so sorry. Sorry for everything.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccecd3"
    },
    {
      "_id": "5cd96e05de30eff6ebccecd4",
      "dialog": "Let's get you out of here.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccecd4"
    },
    {
      "_id": "5cd96e05de30eff6ebccecd6",
      "dialog": "And that's for my old gaffer!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccecd6"
    },
    {
      "_id": "5cd96e05de30eff6ebccecfb",
      "dialog": "Back!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccecfb"
    },
    {
      "_id": "5cd96e05de30eff6ebccecfc",
      "dialog": "Mr Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccecfc"
    },
    {
      "_id": "5cd96e05de30eff6ebccecfe",
      "dialog": "Oh no! Frodo, Mr Frodo. Wake up. Don't leave me here alone. Don't go where I can't follow. Wake up. Not asleep. Dead.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccecfe"
    },
    {
      "_id": "5cd96e05de30eff6ebccecff",
      "dialog": "You get back you scum!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebccecff"
    },
    {
      "_id": "5cd96e05de30eff6ebcced00",
      "dialog": "What's this?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebcced00"
    },
    {
      "_id": "5cd96e05de30eff6ebcced02",
      "dialog": "Killed another one has she?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcced02"
    },
    {
      "_id": "5cd96e05de30eff6ebcced03",
      "dialog": "No. This fellow ain't dead.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebcced03"
    },
    {
      "_id": "5cd96e05de30eff6ebcced04",
      "dialog": "Not dead.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced04"
    },
    {
      "_id": "5cd96e05de30eff6ebcced06",
      "dialog": "She jabs him with her stinger and he goes as limp as a boned fish aaa' then she has her way with them. That's how she likes to feed. Fresh blood. Get him to the Tower!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebcced06"
    },
    {
      "_id": "5cd96e05de30eff6ebcced07",
      "dialog": "Samwise you fool.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced07"
    },
    {
      "_id": "5cd96e05de30eff6ebcced0e",
      "dialog": "The house of his spirit crumbles. He is burning. Already burning.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcced0e"
    },
    {
      "_id": "5cd96e05de30eff6ebcced0f",
      "dialog": "Then he'll wish he'd never been born.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa45",
      "id": "5cd96e05de30eff6ebcced0f"
    },
    {
      "_id": "5cd96e05de30eff6ebcced14",
      "dialog": "This scum will be awake in a couple of hours.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcced14"
    },
    {
      "_id": "5cd96e05de30eff6ebcced17",
      "dialog": "They're not coming from the North! To the river quick, quick!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcef",
      "id": "5cd96e05de30eff6ebcced17"
    },
    {
      "_id": "5cd96e05de30eff6ebcced18",
      "dialog": "Go, come on!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc95",
      "id": "5cd96e05de30eff6ebcced18"
    },
    {
      "_id": "5cd96e05de30eff6ebcced1b",
      "dialog": "Faster! Draw swords.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcced1b"
    },
    {
      "_id": "5cd96e05de30eff6ebcced1c",
      "dialog": "Hold! Hold them!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcced1c"
    },
    {
      "_id": "5cd96e05de30eff6ebcced1d",
      "dialog": "What?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcced1d"
    },
    {
      "_id": "5cd96e05de30eff6ebcced1e",
      "dialog": "Kill him.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa96",
      "id": "5cd96e05de30eff6ebcced1e"
    },
    {
      "_id": "5cd96e05de30eff6ebcced1f",
      "dialog": "Amon D'n.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcced1f"
    },
    {
      "_id": "5cd96e05de30eff6ebcced20",
      "dialog": "Gondor calls for aid.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcced20"
    },
    {
      "_id": "5cd96e05de30eff6ebcced21",
      "dialog": "And Rohan will answer! Muster the Rohirrim. Assemble the army at Dunharrow, as many men as can be found. You have two days. On the third, we ride for Gondor' and war.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcced21"
    },
    {
      "_id": "5cd96e05de30eff6ebcced22",
      "dialog": "Forward!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebcced22"
    },
    {
      "_id": "5cd96e05de30eff6ebcced24",
      "dialog": "Hope is kindled!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcced24"
    },
    {
      "_id": "5cd96e05de30eff6ebcced26",
      "dialog": "The beacons of Minas Tirith! The beacons are lit!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcced26"
    },
    {
      "_id": "5cd96e05de30eff6ebcced28",
      "dialog": "The beacon! The beacon of Amon Dîn is lit.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcced28"
    },
    {
      "_id": "5cd96e05de30eff6ebcced30",
      "dialog": "It's too late. It's over. They've taken it Sam, they took the Ring!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcced30"
    },
    {
      "_id": "5cd96e05de30eff6ebcced34",
      "dialog": "Come on Mr Frodo. We'd best find you some clothes. You can't go walking through Mordor in nowt but your skin.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced34"
    },
    {
      "_id": "5cd96e05de30eff6ebcced35",
      "dialog": "We did it Mr Frodo. We made it to Mordor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced35"
    },
    {
      "_id": "5cd96e05de30eff6ebcced36",
      "dialog": "There are so many of them. We'll never get through unseen.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcced36"
    },
    {
      "_id": "5cd96e05de30eff6ebcced37",
      "dialog": "It's Him, the Eye!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcced37"
    },
    {
      "_id": "5cd96e05de30eff6ebcced38",
      "dialog": "We have to go in there Mr Frodo. There's nothing for it. Come on let's just make it down the hill for starters.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced38"
    },
    {
      "_id": "5cd96e05de30eff6ebcced39",
      "dialog": "Frodo has passed beyond my sight. The darkness is deepening.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcced39"
    },
    {
      "_id": "5cd96e05de30eff6ebcced3a",
      "dialog": "I thought I'd lost you. So I took it, only for safekeeping.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced3a"
    },
    {
      "_id": "5cd96e05de30eff6ebcced3b",
      "dialog": "Begging your pardon but they haven't.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced3b"
    },
    {
      "_id": "5cd96e05de30eff6ebcced3c",
      "dialog": "Give it to me! Give me the Ring Sam. Sam! Give me the Ring. You must understand. The Ring is my burden. It will destroy you Sam.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcced3c"
    },
    {
      "_id": "5cd96e05de30eff6ebcced3d",
      "dialog": "It's only a matter of time. He has suffered a defeat, yes, but behind the walls of Mordor our enemy is regrouping.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcced3d"
    },
    {
      "_id": "5cd96e05de30eff6ebcced3e",
      "dialog": "If Sauron had the Ring we would know it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcced3e"
    },
    {
      "_id": "5cd96e05de30eff6ebcced45",
      "dialog": "Because 10,000 Orcs now stand between Frodo and Mount Doom.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebcced45"
    },
    {
      "_id": "5cd96e05de30eff6ebcced46",
      "dialog": "Let him stay there! Let him rot! Why should we care?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebcced46"
    },
    {
      "_id": "5cd96e05de30eff6ebcced57",
      "dialog": "It must be getting near teatime. Leastways it would be in decent places where there is still teatime.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced57"
    },
    {
      "_id": "5cd96e05de30eff6ebcced58",
      "dialog": "We're not in decent places.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebcced58"
    },
    {
      "_id": "5cd96e05de30eff6ebcced5b",
      "dialog": "It's just a feeling. I don't think I'll be coming back.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcced5b"
    },
    {
      "_id": "5cd96e05de30eff6ebcced5d",
      "dialog": "Yes you will. Of course you will. That's just morbid thinking. We're going there and back again just like Mr Bilbo. You'll see.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced5d"
    },
    {
      "_id": "5cd96e05de30eff6ebcced5e",
      "dialog": "I think these lands were once part of the Kingdom of Gondor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcced5e"
    },
    {
      "_id": "5cd96e05de30eff6ebcced5f",
      "dialog": "Mr Frodo? What is it?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced5f"
    },
    {
      "_id": "5cd96e05de30eff6ebcced63",
      "dialog": "Mr Frodo, look! The King has got a crown again.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebcced63"
    },
    {
      "_id": "5cd96e05de30eff6ebcced68",
      "dialog": "Long ago, when there was a King.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebcced68"
    },
    {
      "_id": "5cd96e05de30eff6ebcced8c",
      "dialog": "He's not dead. HE'S NOT DEAD, NO! NO! He's not dead.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcced8c"
    },
    {
      "_id": "5cd96e05de30eff6ebcced8d",
      "dialog": "Farewell Peregrin son of Paladin.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcced8d"
    },
    {
      "_id": "5cd96e05de30eff6ebcced8e",
      "dialog": "NO! NO!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcced8e"
    },
    {
      "_id": "5cd96e05de30eff6ebcced90",
      "dialog": "I release you from my service. Go now and die and what way seems best to you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebcced90"
    },
    {
      "_id": "5cd96e05de30eff6ebcced91",
      "dialog": "Come on soldier, move it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcced91"
    },
    {
      "_id": "5cd96e05de30eff6ebcced93",
      "dialog": "Hurry along there, hurry along.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcced93"
    },
    {
      "_id": "5cd96e05de30eff6ebcced94",
      "dialog": "Gandalf! Where's Gandalf?, GANDALF!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebcced94"
    },
    {
      "_id": "5cd96e05de30eff6ebcceda4",
      "dialog": "Gamling.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcceda4"
    },
    {
      "_id": "5cd96e05de30eff6ebcceda5",
      "dialog": "Very good sir.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebcceda5"
    },
    {
      "_id": "5cd96e05de30eff6ebcceda6",
      "dialog": "My lord!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0e",
      "id": "5cd96e05de30eff6ebcceda6"
    },
    {
      "_id": "5cd96e05de30eff6ebcceda7",
      "dialog": "Make haste across the Riddermark. Summon every able-bodied man to Dunharrow.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcceda7"
    },
    {
      "_id": "5cd96e05de30eff6ebcceda8",
      "dialog": "I will.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0e",
      "id": "5cd96e05de30eff6ebcceda8"
    },
    {
      "_id": "5cd96e05de30eff6ebcceda9",
      "dialog": "Do you ride with us?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebcceda9"
    },
    {
      "_id": "5cd96e05de30eff6ebccedaa",
      "dialog": "Just to the encampment. It's tradition for the women of the court to farewell the men. The men have found their captain. They will follow you into battle. Even to death. You have given us hope.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebccedaa"
    },
    {
      "_id": "5cd96e05de30eff6ebccedab",
      "dialog": "Excuse me! I have a sword. Please accept it! I offer you my service Theoden King.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccedab"
    },
    {
      "_id": "5cd96e05de30eff6ebccedac",
      "dialog": "And gladly, I accept it. You shall be Meriadoc, esquire of Rohan.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccedac"
    },
    {
      "_id": "5cd96e05de30eff6ebccedad",
      "dialog": "Your kinsmen may have no need to ride to war. I fear war already marches on their own lands.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccedad"
    },
    {
      "_id": "5cd96e05de30eff6ebccedae",
      "dialog": "Now is the hour, Riders of Rohan. Oaths you have taken. Now fulfil them all, to Lord and Land! Hah!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebccedae"
    },
    {
      "_id": "5cd96e05de30eff6ebccedb5",
      "dialog": "Horse men! I wish I could muster an army of Dwarves, fully armed and filthy.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccedb5"
    },
    {
      "_id": "5cd96e05de30eff6ebccedbd",
      "dialog": "No. There is still hope for Frodo. He needs time and safe passage across the plains of Gorgoroth. We can give him that.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccedbd"
    },
    {
      "_id": "5cd96e05de30eff6ebccedbe",
      "dialog": "How?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccedbe"
    },
    {
      "_id": "5cd96e05de30eff6ebccedbf",
      "dialog": "Draw out Sauron's armies. Empty his lands. Then we gather our full strength and march on the Black Gate.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccedbf"
    },
    {
      "_id": "5cd96e05de30eff6ebccedc0",
      "dialog": "We cannot achieve victory through strength of arms.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebccedc0"
    },
    {
      "_id": "5cd96e05de30eff6ebccedc2",
      "dialog": "Certainty of death, small chance of success, what are we waiting for?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccedc2"
    },
    {
      "_id": "5cd96e05de30eff6ebccedc3",
      "dialog": "Sauron will suspect a trap. He will not take the bait.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccedc3"
    },
    {
      "_id": "5cd96e05de30eff6ebccedc4",
      "dialog": "Oh, I think he will.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccedc4"
    },
    {
      "_id": "5cd96e05de30eff6ebccedc5",
      "dialog": "Long have you hunted me. Long have I eluded you. No more! Behold, the Sword of Elendil!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccedc5"
    },
    {
      "_id": "5cd96e05de30eff6ebccedcc",
      "dialog": "Not for ourselves. But we can give Frodo his chance if we keep Sauron's eye fixed upon us. Keep him blind to all else that moves.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccedcc"
    },
    {
      "_id": "5cd96e05de30eff6ebccedcd",
      "dialog": "I've sent him to his death.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccedcd"
    },
    {
      "_id": "5cd96e05de30eff6ebccedce",
      "dialog": "A diversion.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccedce"
    },
    {
      "_id": "5cd96e05de30eff6ebccede5",
      "dialog": "So I imagine this is just a ceremonial position. I mean, they don't actually expect me to do any fighting, do they?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccede5"
    },
    {
      "_id": "5cd96e05de30eff6ebccede6",
      "dialog": "You're in the service of the steward now. You'll have to do as you are told Peregrin Took.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccede6"
    },
    {
      "_id": "5cd96e05de30eff6ebccede7",
      "dialog": "Ridiculous Hobbit! Guard of the Citadel!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccede7"
    },
    {
      "_id": "5cd96e05de30eff6ebccede8",
      "dialog": "Thank you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccede8"
    },
    {
      "_id": "5cd96e05de30eff6ebccedea",
      "dialog": "Come on, Hobbits! Mustn't stop now. This way!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccedea"
    },
    {
      "_id": "5cd96e05de30eff6ebccedeb",
      "dialog": "There's no more stars! Is it time?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccedeb"
    },
    {
      "_id": "5cd96e05de30eff6ebccedec",
      "dialog": "Yes.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccedec"
    },
    {
      "_id": "5cd96e05de30eff6ebccedee",
      "dialog": "It's so quiet.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccedee"
    },
    {
      "_id": "5cd96e05de30eff6ebccedef",
      "dialog": "It's the deep breath before the plunge.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccedef"
    },
    {
      "_id": "5cd96e05de30eff6ebccedf0",
      "dialog": "I don't want to be in a battle. But waiting on the edge of one I can't escape is even worse. Is there any hope Gandalf, for Frodo and Sam?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccedf0"
    },
    {
      "_id": "5cd96e05de30eff6ebccedf1",
      "dialog": "There never was much hope. Just a fool's hope. Our enemy is ready. His full strength's gathered. Not only orcs, but men as well, Legions of Haradrim from the South, mercenaries from the coast, All will answer Mordor's call.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccedf1"
    },
    {
      "_id": "5cd96e05de30eff6ebccedf2",
      "dialog": "Come on!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebccedf2"
    },
    {
      "_id": "5cd96e05de30eff6ebccee73",
      "dialog": "Gandalf?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccee73"
    },
    {
      "_id": "5cd96e05de30eff6ebccee74",
      "dialog": "Sauron has yet to show his deadliest servant. The one who will lead Mordor's army in war. The one they say no living man can kill. The Witch King of Angmar. You've met him before. He stabbed Frodo on Weathertop. He is the lord of the Nazg'l. The greatest of the nine.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccee74"
    },
    {
      "_id": "5cd96e05de30eff6ebccee75",
      "dialog": "The Dead City! Very nasty place full of enemies.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccee75"
    },
    {
      "_id": "5cd96e05de30eff6ebccee76",
      "dialog": "Quick, quick! They will see, they will see!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccee76"
    },
    {
      "_id": "5cd96e05de30eff6ebccee77",
      "dialog": "Come away, come away. Look we have found it. The way into Mordor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccee77"
    },
    {
      "_id": "5cd96e05de30eff6ebccee78",
      "dialog": "The secret stair. Climb.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccee78"
    },
    {
      "_id": "5cd96e05de30eff6ebccee79",
      "dialog": "But we have the white wizard. That's got to count for something.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccee79"
    },
    {
      "_id": "5cd96e05de30eff6ebccee7a",
      "dialog": "Not that way!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccee7a"
    },
    {
      "_id": "5cd96e05de30eff6ebccee7b",
      "dialog": "This will be the end of Gondor as we know it. Here the hammer stroke will fall hardest. If the river is taken, if the garrison at Osgiliath falls, the last defence of this city will be gone.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccee7b"
    },
    {
      "_id": "5cd96e05de30eff6ebccee7c",
      "dialog": "Whats it doing?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccee7c"
    },
    {
      "_id": "5cd96e05de30eff6ebccee7d",
      "dialog": "No!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccee7d"
    },
    {
      "_id": "5cd96e05de30eff6ebccee7e",
      "dialog": "They're calling me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccee7e"
    },
    {
      "_id": "5cd96e05de30eff6ebccee8f",
      "dialog": "No! Mr Frodo!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccee8f"
    },
    {
      "_id": "5cd96e05de30eff6ebccee9e",
      "dialog": "Hail!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebccee9e"
    },
    {
      "_id": "5cd96e05de30eff6ebccee9f",
      "dialog": "No pauses, no spills.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa5a",
      "id": "5cd96e05de30eff6ebccee9f"
    },
    {
      "_id": "5cd96e05de30eff6ebcceea5",
      "dialog": "Tonight we remember those who gave their blood to defend this country.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcceea5"
    },
    {
      "_id": "5cd96e05de30eff6ebcceeaa",
      "dialog": "Hail the victorious dead",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebcceeaa"
    },
    {
      "_id": "5cd96e05de30eff6ebccef10",
      "dialog": "Hide, hide!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccef10"
    },
    {
      "_id": "5cd96e05de30eff6ebccef11",
      "dialog": "No!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccef11"
    },
    {
      "_id": "5cd96e05de30eff6ebccef12",
      "dialog": "I can feel his blade.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccef12"
    },
    {
      "_id": "5cd96e05de30eff6ebccef13",
      "dialog": "We come to it at last.The great battle of our time.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccef13"
    },
    {
      "_id": "5cd96e05de30eff6ebccef14",
      "dialog": "Come away Hobbits. We climb. We must climb.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccef14"
    },
    {
      "_id": "5cd96e05de30eff6ebccef15",
      "dialog": "The board is set, the pieces are moving.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccef15"
    },
    {
      "_id": "5cd96e05de30eff6ebccef16",
      "dialog": "Up, up, up the stairs we go. And then it's into the tunnel.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccef16"
    },
    {
      "_id": "5cd96e05de30eff6ebccef17",
      "dialog": "Hey, what's in this tunnel? , You listen to me! You listen good and proper. Anything happens to him, you'll have me to answer to. One sniff that something's not right, one hair that stands up on the back of my neck, its over. No more slinker, no more stinker. You're gone. Got it? I'm watching you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccef17"
    },
    {
      "_id": "5cd96e05de30eff6ebccef18",
      "dialog": "What was that about?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccef18"
    },
    {
      "_id": "5cd96e05de30eff6ebccef1a",
      "dialog": "Nothing. Just clearing something up.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccef1a"
    },
    {
      "_id": "5cd96e05de30eff6ebccef23",
      "dialog": "Take her by the safest road. A ship lies anchored in the Grey Havens. It waits to carry her across the sea. The last journey of Arwen Und'miel.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebccef23"
    },
    {
      "_id": "5cd96e05de30eff6ebccef25",
      "dialog": "Arwen.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebccef25"
    },
    {
      "_id": "5cd96e05de30eff6ebccef26",
      "dialog": "You have the gift of foresight. What did you see?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccef26"
    },
    {
      "_id": "5cd96e05de30eff6ebccef27",
      "dialog": "I looked into your future and I saw death.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebccef27"
    },
    {
      "_id": "5cd96e05de30eff6ebccef28",
      "dialog": "But there is also life. You saw there was a child. You saw my son.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccef28"
    },
    {
      "_id": "5cd96e05de30eff6ebccef2b",
      "dialog": "Lady Arwen we cannot delay. My lady!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe3667ed9587226e7949e",
      "id": "5cd96e05de30eff6ebccef2b"
    },
    {
      "_id": "5cd96e05de30eff6ebccef2c",
      "dialog": "Tell me what you have seen.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccef2c"
    },
    {
      "_id": "5cd96e05de30eff6ebccef2d",
      "dialog": "There is nothing for you here only death.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebccef2d"
    },
    {
      "_id": "5cd96e05de30eff6ebccef38",
      "dialog": "So' it's a drinking game?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccef38"
    },
    {
      "_id": "5cd96e05de30eff6ebccef39",
      "dialog": "Aye!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebccef39"
    },
    {
      "_id": "5cd96e05de30eff6ebccef3c",
      "dialog": "Last one standing wins heh heh heh!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccef3c"
    },
    {
      "_id": "5cd96e05de30eff6ebccef3d",
      "dialog": "Lets drink to Victory! To Victory!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbe49b7ed9587226e794a0",
      "id": "5cd96e05de30eff6ebccef3d"
    },
    {
      "_id": "5cd96e05de30eff6ebccef3e",
      "dialog": "West' Aragorn, hal",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebccef3e"
    },
    {
      "_id": "5cd96e05de30eff6ebccef3f",
      "dialog": "And no regurgitation!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccef3f"
    },
    {
      "_id": "5cd96e05de30eff6ebccef40",
      "dialog": "I am very happy for you. He is an honourable man.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccef40"
    },
    {
      "_id": "5cd96e05de30eff6ebccef41",
      "dialog": "Heh heh heh heh,Here, here. Raaar it's the dwarves that go swimming with little, hairy women haha.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccef41"
    },
    {
      "_id": "5cd96e05de30eff6ebccef42",
      "dialog": "I feel something. A slight tingle in my fingers. I think it's affecting me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccef42"
    },
    {
      "_id": "5cd96e05de30eff6ebccef43",
      "dialog": "heh heh heh, what did I say? He can't hold his liquor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd23",
      "id": "5cd96e05de30eff6ebccef43"
    },
    {
      "_id": "5cd96e05de30eff6ebccef44",
      "dialog": "Game over!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccef44"
    },
    {
      "_id": "5cd96e05de30eff6ebccef45",
      "dialog": "Oh you can search far and wide, you can drink the whole town dry, but you'll never find a beer so brown, but you'll never find a beer so brown, as the one we drink in our hometown, as the one we drink in our hometown! You can drink your fancy ales, you can drink them by the flagon, but the only brew for the brave and true!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccef45"
    },
    {
      "_id": "5cd96e05de30eff6ebccef47",
      "dialog": "It was not Theoden of Rohan who led our people to victory.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccef47"
    },
    {
      "_id": "5cd96e05de30eff6ebccef49",
      "dialog": "Ach, don't listen to me. You are young and tonight is for you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccef49"
    },
    {
      "_id": "5cd96e05de30eff6ebccef4a",
      "dialog": "You are both honourable men.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebccef4a"
    },
    {
      "_id": "5cd96e05de30eff6ebccefb9",
      "dialog": "Nothing is certain.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebccefb9"
    },
    {
      "_id": "5cd96e05de30eff6ebccefbb",
      "dialog": "Some things are certain.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccefbb"
    },
    {
      "_id": "5cd96e05de30eff6ebccefbc",
      "dialog": "If I leave him now, I will regret it forever. It is time.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccefbc"
    },
    {
      "_id": "5cd96e05de30eff6ebccefbd",
      "dialog": "From the ashes of fire shall be woken, A light from the shadow shall spring, Renewed shall be blade that was broken, The crownless again shall be king.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccefbd"
    },
    {
      "_id": "5cd96e05de30eff6ebccefbe",
      "dialog": "Reforge the sword' ada.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccefbe"
    },
    {
      "_id": "5cd96e05de30eff6ebccefbf",
      "dialog": "Your hands are cold. The life of the Eldar is leaving you.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebccefbf"
    },
    {
      "_id": "5cd96e05de30eff6ebccefc0",
      "dialog": "That future is almost gone.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfcc8",
      "id": "5cd96e05de30eff6ebccefc0"
    },
    {
      "_id": "5cd96e05de30eff6ebccefc2",
      "dialog": "But it is not lost.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccefc2"
    },
    {
      "_id": "5cd96e05de30eff6ebccefc3",
      "dialog": "We have just passed into the realm of Gondor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccefc3"
    },
    {
      "_id": "5cd96e05de30eff6ebccefc4",
      "dialog": "Yes the white tree of Gondor. The tree of the King. Lord Denethor however, is not the King. He is a steward only, a caretaker of the throne.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccefc4"
    },
    {
      "_id": "5cd96e05de30eff6ebccefc5",
      "dialog": "Now listen carefully. Lord Denethor is Boromir's father. To give him news of his beloved son's death would be most unwise. And do not mention Frodo or the Ring. And say nothing of Aragorn either. In fact, its better if you don't speak at all Peregrin Took.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccefc5"
    },
    {
      "_id": "5cd96e05de30eff6ebccefc6",
      "dialog": "Hail Denethor son of Ecthelion, Lord and Steward of Gondor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccefc6"
    },
    {
      "_id": "5cd96e05de30eff6ebccefc7",
      "dialog": "It's the tree! Gandalf, Gandalf.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccefc7"
    },
    {
      "_id": "5cd96e05de30eff6ebccefc8",
      "dialog": "Minas Tirith. City of Kings.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccefc8"
    },
    {
      "_id": "5cd96e05de30eff6ebccefcf",
      "dialog": "This was my choice. Ada, whether by your will or not there is no ship now that can bear me hence.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc07",
      "id": "5cd96e05de30eff6ebccefcf"
    },
    {
      "_id": "5cd96e05de30eff6ebccefd5",
      "dialog": "No news of Frodo?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccefd5"
    },
    {
      "_id": "5cd96e05de30eff6ebccefd6",
      "dialog": "No word. Nothing.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccefd6"
    },
    {
      "_id": "5cd96e05de30eff6ebccefd7",
      "dialog": "We have time. Every day Frodo moves closer to Mordor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccefd7"
    },
    {
      "_id": "5cd96e05de30eff6ebccefd8",
      "dialog": "Do we know that?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccefd8"
    },
    {
      "_id": "5cd96e05de30eff6ebccefd9",
      "dialog": "What does your heart tell you?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccefd9"
    },
    {
      "_id": "5cd96e05de30eff6ebccefda",
      "dialog": "That Frodo is alive. Yes' yes he's alive.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccefda"
    },
    {
      "_id": "5cd96e05de30eff6ebccefdb",
      "dialog": "Too risky. Too risky. Thieves. They stole it from us. Kill them, kill them, kill them both!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccefdb"
    },
    {
      "_id": "5cd96e05de30eff6ebccefdc",
      "dialog": "Comes from the Green Dragon!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccefdc"
    },
    {
      "_id": "5cd96e05de30eff6ebccefdd",
      "dialog": "No!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccefdd"
    },
    {
      "_id": "5cd96e05de30eff6ebccefde",
      "dialog": "Sshh, quiet, mustn't wake them. Mustn't ruin it now.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccefde"
    },
    {
      "_id": "5cd96e05de30eff6ebccefdf",
      "dialog": "But they knows, they knows, they suspects us!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccefdf"
    },
    {
      "_id": "5cd96e05de30eff6ebccefe0",
      "dialog": "Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccefe0"
    },
    {
      "_id": "5cd96e05de30eff6ebccefe1",
      "dialog": "What's it saying my precious, my love? Is Smeagol losing his nerve?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccefe1"
    },
    {
      "_id": "5cd96e05de30eff6ebccefe3",
      "dialog": "Thank you! I win!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccefe3"
    },
    {
      "_id": "5cd96e05de30eff6ebccf01e",
      "dialog": "I come with tidings in this dark hour and with counsel.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf01e"
    },
    {
      "_id": "5cd96e05de30eff6ebccf01f",
      "dialog": "Perhaps you come to explain this.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebccf01f"
    },
    {
      "_id": "5cd96e05de30eff6ebccf020",
      "dialog": "Perhaps you have come to tell me why my son is dead.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebccf020"
    },
    {
      "_id": "5cd96e05de30eff6ebccf022",
      "dialog": "Boromir died to save us my kinsman and me. He fell defending us from many foes.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf022"
    },
    {
      "_id": "5cd96e05de30eff6ebccf023",
      "dialog": "Pippin.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf023"
    },
    {
      "_id": "5cd96e05de30eff6ebccf024",
      "dialog": "I offer you my service, such as it is in payment of this debt.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf024"
    },
    {
      "_id": "5cd96e05de30eff6ebccf027",
      "dialog": "This is my first command to you. How did you escape and my son did not? So mighty as man as he was.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebccf027"
    },
    {
      "_id": "5cd96e05de30eff6ebccf028",
      "dialog": "The mightiest man may be slain by one arrow and Boromir was pierced by many.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf028"
    },
    {
      "_id": "5cd96e05de30eff6ebccf029",
      "dialog": "Get up!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf029"
    },
    {
      "_id": "5cd96e05de30eff6ebccf02a",
      "dialog": "You think you are wise Mithrandir. Yet for all your subtleties you have not wisdom. Do you think the eyes of the White Tower are blind? I have seen more than you know. With your left hand you would use me as a shield against Mordor and with your right you would seek to supplant me. I know who rides with Theoden of Rohan. Oh yes, word has reached my ears of this Aragorn, son of Arathorn. And I tell you now. I will not bow to this Ranger from the North. Last of a ragged house long bereft of Lordship.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebccf02a"
    },
    {
      "_id": "5cd96e05de30eff6ebccf02b",
      "dialog": "Authority is not given to you to deny the return of the King, steward.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf02b"
    },
    {
      "_id": "5cd96e05de30eff6ebccf02c",
      "dialog": "Come!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf02c"
    },
    {
      "_id": "5cd96e05de30eff6ebccf02d",
      "dialog": "All had turned to vain ambition. He would use even his grief as a cloak! A thousand years this city has stood and now at the whim of a madman it will fall! And the white tree, the tree of the King will never bloom again.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf02d"
    },
    {
      "_id": "5cd96e05de30eff6ebccf031",
      "dialog": "My lord, there will be a time to grieve for Boromir but it is not now. War is coming. The enemy is on your doorstep. As steward, you are charged with the defence of this city. Where are Gondor's armies? You still have friends. You are not alone in this fight. Send word to Theoden of Rohan. Light the beacons.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf031"
    },
    {
      "_id": "5cd96e05de30eff6ebccf032",
      "dialog": "The rule of Gondor is mine and no others!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfca1",
      "id": "5cd96e05de30eff6ebccf032"
    },
    {
      "_id": "5cd96e05de30eff6ebccf03e",
      "dialog": "No! No! Never! Smeagol hates nasty Hobbitses. Smeagol wants to see them'. Dead!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf03e"
    },
    {
      "_id": "5cd96e05de30eff6ebccf03f",
      "dialog": "And we will! Smeagol did it once, he can do it again! Its ours! Ours!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf03f"
    },
    {
      "_id": "5cd96e05de30eff6ebccf040",
      "dialog": "We must get the precious! We must get it back!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf040"
    },
    {
      "_id": "5cd96e05de30eff6ebccf041",
      "dialog": "Patience! Patience my love! First we must lead them to her!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf041"
    },
    {
      "_id": "5cd96e05de30eff6ebccf042",
      "dialog": "We lead them to the winding stair.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf042"
    },
    {
      "_id": "5cd96e05de30eff6ebccf043",
      "dialog": "Yes, the stairs and then?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf043"
    },
    {
      "_id": "5cd96e05de30eff6ebccf044",
      "dialog": "And when they go in, there's no coming out. She's always hungry. She always needs to' feed. She must eat. All she gets is filthy Orcses.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf044"
    },
    {
      "_id": "5cd96e05de30eff6ebccf045",
      "dialog": "No, not very nice at all, my love. She hungers for sweeter meats. Hobbit meat. And when she throws away the bones and the empty clothes, then we will find it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf045"
    },
    {
      "_id": "5cd96e05de30eff6ebccf046",
      "dialog": "And take it for Meee!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf046"
    },
    {
      "_id": "5cd96e05de30eff6ebccf047",
      "dialog": "Yes, we meant for us! Gollum, gollum. The precious will be ours once the Hobbitses are dead!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf047"
    },
    {
      "_id": "5cd96e05de30eff6ebccf048",
      "dialog": "For us.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf048"
    },
    {
      "_id": "5cd96e05de30eff6ebccf04a",
      "dialog": "Up, up, up the stairs we go until we come to the tunnel.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf04a"
    },
    {
      "_id": "5cd96e05de30eff6ebccf04b",
      "dialog": "And they doesn't taste very nice, does they Precious?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf04b"
    },
    {
      "_id": "5cd96e05de30eff6ebccf06a",
      "dialog": "Yes, there it lies. This city has dwelt ever in the sight of its shadow.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf06a"
    },
    {
      "_id": "5cd96e05de30eff6ebccf06b",
      "dialog": "A storm is coming.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf06b"
    },
    {
      "_id": "5cd96e05de30eff6ebccf06c",
      "dialog": "This is not the weather of the world. This is a device of Sauron's making. A broil of fume he sends ahead of his host. The Orcs of Mordor have no love of daylight, so he covers the face of the sun to ease their passage along the road to war. When the shadow of Mordor reaches this city it will begin.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf06c"
    },
    {
      "_id": "5cd96e05de30eff6ebccf06d",
      "dialog": "Well' Minas Tirith' very impressive. So where are off to next?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf06d"
    },
    {
      "_id": "5cd96e05de30eff6ebccf06e",
      "dialog": "Oh, it's too late for that Peregrin. There's no leaving this city. Help must come to us.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf06e"
    },
    {
      "_id": "5cd96e05de30eff6ebccf070",
      "dialog": "They guard it because they have hope. A faint and fading hope that one day it will flower. That a king will come and this city will be as it once was before it fell into decay. The old wisdom born out of the west was forsaken. Kings made tombs more splendid than the houses of the living and counted the old names of their descent, dearer than the names of their sons. Childless lords sat in aged halls musing on heraldry or in high, cold towers asking questions of the stars. And so the people of Gondor fell into ruin. The line of Kings failed. The white tree withered. The rule of Gondor was given over to lesser men.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf070"
    },
    {
      "_id": "5cd96e05de30eff6ebccf071",
      "dialog": "Why are they still guarding it?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf071"
    },
    {
      "_id": "5cd96e05de30eff6ebccf072",
      "dialog": "Mordor.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf072"
    },
    {
      "_id": "5cd96e05de30eff6ebccf07d",
      "dialog": "You treacherous little toad!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccf07d"
    },
    {
      "_id": "5cd96e05de30eff6ebccf07f",
      "dialog": "No Sam! Leave him alone!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccf07f"
    },
    {
      "_id": "5cd96e05de30eff6ebccf080",
      "dialog": "No, no! Master!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf080"
    },
    {
      "_id": "5cd96e05de30eff6ebccf081",
      "dialog": "You miserable little maggot! I'll stove your head in!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccf081"
    },
    {
      "_id": "5cd96e05de30eff6ebccf082",
      "dialog": "I heard it from his own mouth. He means to murder us.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccf082"
    },
    {
      "_id": "5cd96e05de30eff6ebccf083",
      "dialog": "Never! Smeagol wouldn't hurt a fly! Aaaagh he is a horrid, fat Hobbit who hates Smeagol and who makes up nasty lies!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf083"
    },
    {
      "_id": "5cd96e05de30eff6ebccf084",
      "dialog": "Sam!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccf084"
    },
    {
      "_id": "5cd96e05de30eff6ebccf085",
      "dialog": "I don't care! I can't do it Mr Frodo! I won't wait around for him to kill us!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccf085"
    },
    {
      "_id": "5cd96e05de30eff6ebccf086",
      "dialog": "I'm not sending him away.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccf086"
    },
    {
      "_id": "5cd96e05de30eff6ebccf087",
      "dialog": "You don't see it do you? He's a villain.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccf087"
    },
    {
      "_id": "5cd96e05de30eff6ebccf088",
      "dialog": "We can't do this by ourselves Sam. Not without a guide. I need you on my side.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccf088"
    },
    {
      "_id": "5cd96e05de30eff6ebccf08b",
      "dialog": "Waaaah!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe9e",
      "id": "5cd96e05de30eff6ebccf08b"
    },
    {
      "_id": "5cd96e05de30eff6ebccf08d",
      "dialog": "If you scare him off then we are lost!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccf08d"
    },
    {
      "_id": "5cd96e05de30eff6ebccf093",
      "dialog": "Call me a liar? You're a liar!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccf093"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0b6",
      "dialog": "What time is it?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebccf0b6"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0b8",
      "dialog": "I'm on your side Mr Frodo",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd0d",
      "id": "5cd96e05de30eff6ebccf0b8"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0b9",
      "dialog": "I know Sam, I know. Trust me. Come Smeagol.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc15",
      "id": "5cd96e05de30eff6ebccf0b9"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0ba",
      "dialog": "I dreamed I saw a great wave climbing over green lands and above the hills. I stood upon the brink. It was utterly dark in the abyss before my feet. A light shone behind me but I could not turn, I could only stand there, waiting.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cdbdecb6dc0baeae48cfa59",
      "id": "5cd96e05de30eff6ebccf0ba"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0bb",
      "dialog": "Night changes many thoughts. Sleep Eowyn. Sleep while you can.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccf0bb"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0bc",
      "dialog": "What are you doing?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0bc"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0bd",
      "dialog": "Pippin! Are you mad?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0bd"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0be",
      "dialog": "The stars are veiled. Something stirs in the East, a sleepless malice , The eye of the enemy is moving.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccf0be"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0bf",
      "dialog": "Put it back!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0bf"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0c0",
      "dialog": "Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0c0"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0c1",
      "dialog": "Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0c1"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0c2",
      "dialog": "I just want to look at it, just one more time.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf0c2"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0c3",
      "dialog": "Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0c3"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0c4",
      "dialog": "No!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0c4"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0eb",
      "dialog": "Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0eb"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0ec",
      "dialog": "He is here!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfd81",
      "id": "5cd96e05de30eff6ebccf0ec"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0ed",
      "dialog": "I see you!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea5",
      "id": "5cd96e05de30eff6ebccf0ed"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0ee",
      "dialog": "Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0ee"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0ef",
      "dialog": "Help! Gandalf help!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0ef"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0f0",
      "dialog": "Help him!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0f0"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0f3",
      "dialog": "Pippin!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf0f3"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0f4",
      "dialog": "No.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf0f4"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0f6",
      "dialog": "Fool of a Took!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf0f6"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0f7",
      "dialog": "Look at me.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf0f7"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0f8",
      "dialog": "Look at me! What did you see?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf0f8"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0fc",
      "dialog": "Gandalf, forgive me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf0fc"
    },
    {
      "_id": "5cd96e05de30eff6ebccf0ff",
      "dialog": "Minas Tirith? Is that what you saw?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf0ff"
    },
    {
      "_id": "5cd96e05de30eff6ebccf101",
      "dialog": "A tree, there was a white tree in a courtyard of stone. It was dead. The city was burning.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf101"
    },
    {
      "_id": "5cd96e05de30eff6ebccf112",
      "dialog": "What did you tell him about Frodo and the Ring?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf112"
    },
    {
      "_id": "5cd96e05de30eff6ebccf113",
      "dialog": "There was no lie in Pippin's eyes. A fool but an honest fool he remains.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf113"
    },
    {
      "_id": "5cd96e05de30eff6ebccf114",
      "dialog": "He told Sauron nothing of Frodo and the Ring. We've been strangely fortunate. Pippin saw in the Palantir a glimpse of the enemy's plan. Sauron moves to strike the city of Minas Tirith.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf114"
    },
    {
      "_id": "5cd96e05de30eff6ebccf115",
      "dialog": "His defeat at Helm's Deep showed our enemy one thing. He knows the Heir of Elendil has come forth, Men are not as weak as he supposed. There is courage still. Strength enough, perhaps, to challenge him. Sauron fears this. He will not risk the peoples of Middle Earth uniting under one banner. He will raze Minas Tirith to the ground, before he sees a King return to the throne of men. If the beacons of Gondor are lit Rohan must be ready for war.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf115"
    },
    {
      "_id": "5cd96e05de30eff6ebccf116",
      "dialog": "Tell me! Why should we ride to the aid of those who did not come to ours? What do we owe Gondor?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe19",
      "id": "5cd96e05de30eff6ebccf116"
    },
    {
      "_id": "5cd96e05de30eff6ebccf117",
      "dialog": "I will go!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccf117"
    },
    {
      "_id": "5cd96e05de30eff6ebccf118",
      "dialog": "And what did you tell him? Speak!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf118"
    },
    {
      "_id": "5cd96e05de30eff6ebccf119",
      "dialog": "I saw' I saw him! I could hear his voice in my head.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf119"
    },
    {
      "_id": "5cd96e05de30eff6ebccf11a",
      "dialog": "He asked me my name. I didn't answer. He hurt me!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf11a"
    },
    {
      "_id": "5cd96e05de30eff6ebccf11b",
      "dialog": "No!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf11b"
    },
    {
      "_id": "5cd96e05de30eff6ebccf11c",
      "dialog": "They must be warned!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccf11c"
    },
    {
      "_id": "5cd96e05de30eff6ebccf128",
      "dialog": "They will be. You must come to Minas Tirith by another road. Follow the river. Look to the black ships. Understand this, things are now in motion that cannot be undone. I ride for Minas Tirith, and I wont be going alone.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf128"
    },
    {
      "_id": "5cd96e05de30eff6ebccf129",
      "dialog": "Where are we going?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf129"
    },
    {
      "_id": "5cd96e05de30eff6ebccf12a",
      "dialog": "Of all the Hobbits, Peregrin Took, you are the worst! Hurry! Hurry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf12a"
    },
    {
      "_id": "5cd96e05de30eff6ebccf12b",
      "dialog": "Why did you look? Why do you always have to look?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf12b"
    },
    {
      "_id": "5cd96e05de30eff6ebccf12c",
      "dialog": "I don't know, I can't help it.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf12c"
    },
    {
      "_id": "5cd96e05de30eff6ebccf12d",
      "dialog": "And you? You're coming with me?, Merry?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf12d"
    },
    {
      "_id": "5cd96e05de30eff6ebccf12e",
      "dialog": "Come on!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf12e"
    },
    {
      "_id": "5cd96e05de30eff6ebccf12f",
      "dialog": "How far is Minas Tirith?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf12f"
    },
    {
      "_id": "5cd96e05de30eff6ebccf130",
      "dialog": "Three days ride as the Nazg'l flies. And you'd better hope we don't have one of those on our tail.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf130"
    },
    {
      "_id": "5cd96e05de30eff6ebccf131",
      "dialog": "Here, something for the road.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf131"
    },
    {
      "_id": "5cd96e05de30eff6ebccf132",
      "dialog": "The last of the Longbottom Leaf?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf132"
    },
    {
      "_id": "5cd96e05de30eff6ebccf133",
      "dialog": "I know you've run out. You smoke too much Pippin.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf133"
    },
    {
      "_id": "5cd96e05de30eff6ebccf134",
      "dialog": "I'm sorry alright? I won't do it again.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf134"
    },
    {
      "_id": "5cd96e05de30eff6ebccf135",
      "dialog": "But, we'll see each other soon?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf135"
    },
    {
      "_id": "5cd96e05de30eff6ebccf136",
      "dialog": "Wont we?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf136"
    },
    {
      "_id": "5cd96e05de30eff6ebccf137",
      "dialog": "Don't you understand? The enemy thinks you have the ring! He is going to be looking for you Pip. They have to get you out of here.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf137"
    },
    {
      "_id": "5cd96e05de30eff6ebccf138",
      "dialog": "I don't know! I don't know whats going to happen.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf138"
    },
    {
      "_id": "5cd96e05de30eff6ebccf139",
      "dialog": "Merry?",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf139"
    },
    {
      "_id": "5cd96e05de30eff6ebccf13a",
      "dialog": "You never can!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf13a"
    },
    {
      "_id": "5cd96e05de30eff6ebccf13b",
      "dialog": "Run, Shadowfax, show us the meaning of haste.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfea0",
      "id": "5cd96e05de30eff6ebccf13b"
    },
    {
      "_id": "5cd96e05de30eff6ebccf13c",
      "dialog": "Merry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfe2e",
      "id": "5cd96e05de30eff6ebccf13c"
    },
    {
      "_id": "5cd96e05de30eff6ebccf13d",
      "dialog": "Merry!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccf13d"
    },
    {
      "_id": "5cd96e05de30eff6ebccf13e",
      "dialog": "He's always followed me everywhere I went since before we were tweens. I would get him into the worst sort of trouble but I was always there to get him out. Now he's gone. Just like Frodo and Sam.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf13e"
    },
    {
      "_id": "5cd96e05de30eff6ebccf13f",
      "dialog": "One thing I've learnt about Hobbits: They are a most hardy folk.",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfbe6",
      "id": "5cd96e05de30eff6ebccf13f"
    },
    {
      "_id": "5cd96e05de30eff6ebccf140",
      "dialog": "Foolhardy maybe. He's a Took!",
      "movie": "5cd95395de30eff6ebccde5d",
      "character": "5cd99d4bde30eff6ebccfc7c",
      "id": "5cd96e05de30eff6ebccf140"
    }
  ],
  "total": 872,
  "limit": 1000,
  "offset": 0,
  "page": 1,
  "pages": 1
}
```

