```
use rand::thread_rng;
use rand::Rng;
use base64::{decode};

fn main() {

    let steins = "el psy ";
    let mut gate = "congroo";
    let mut divergence = 0.000000;
    let mut d_mail = 4.0;
    
    while divergence < 1.00000 {
        divergence = jump(divergence, d_mail);
        gate = enter(WorldLine::α);
        d_mail - 1.0;
        println!("{}", {steins;gate});
        };
    
    gate = enter(WorldLine::β);
    println!("{}", {steins;gate});
    
}

enum WorldLine {
    α ,
    β ,
}

fn enter<'a>(world_line: WorldLine) -> &'a str {
    match world_line {
        WorldLine::α => "aHR0cHM6Ly93d3cueW91dHViZS5jb20vd2F0Y2g/dj1rMkxEQzBzVHNFUQ==",
        WorldLine::β => "aHR0cHM6Ly93d3cueW91dHViZS5jb20vd2F0Y2g/dj03YjFyS3BNZzlLcw==",
    }
}

fn jump(mut divergence: f64, mut d_mail: f64) -> f64 {
    let mut rng = rand::thread_rng();
    divergence = rng.gen();
    (divergence/(divergence.abs()+d_mail)).ceil()
}

```

[playground](https://play.rust-lang.org/?version=stable&mode=debug&edition=2021&gist=3f364950e4f0171c09506352af89410c)

[Bioinformatics in Rust](https://kana4.github.io/bioinformatics_rust_book/Chapter_1/1_0_Introduction.html)

[](./bookseller.gif)

[](https://www.kaggle.com/chrispr)

[](https://hub.docker.com/r/windybasket/public)

[](./thumbsup.gif)
[](http://webcomic.ohtabooks.com/ashita/)

[](https://chap.manganelo.com/manga-ny89218/chapter-1)

[](https://codepen.io/topics/)

[](https://data.stackexchange.com/stackoverflow/queries)

[](https://www.airdna.co/vacation-rental-data/app/jp/hiroshima-ken/naka-ku/overview)

[](https://h2oai.github.io/db-benchmark/)

[](https://www2.deloitte.com/ca/en/pages/about-deloitte/articles/covid-dashboard.html?is=5e8d4f149b0f225dde35ccbe)

[](https://www.shodan.io/search?query=ver2.4+rev0+country%3A%22JP%22+has_screenshot%3Atrue)

[](https://yomi.yoroi.company/upload)

[](https://opendata.rapid7.com/)

[](https://bazaar.abuse.ch/)

[](https://www.exploit-db.com/google-hacking-database)
