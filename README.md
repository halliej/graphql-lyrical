# Lyrical-GraphQL
Starter project from a GraphQL course on Udemy.com

mutation {
  addSong(title: "Cold Night") {
    id
  }
}

mutation {
  addLyricToSong(songId: "58c4221e85defd0527c8ba58", content: "Oh my its a cold night") {
    id
  }
}

{
  songs {
    id
    title
    lyrics {
      content
    }
  }
}

mutation {
  addSong (title: "Dog Call") {
    id
    title
  }
}
