# dsc-395t-algorithms-and-data-structures-spring-2022-boggle-solved
**TO GET THIS SOLUTION VISIT:** [DSC 395T Algorithms and Data Structures — Spring 2022 Boggle Solved](https://www.ankitcodinghub.com/product/dsc-395t-algorithms-and-data-structures-spring-2022-boggle-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;104780&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DSC 395T Algorithms and Data Structures — Spring 2022 Boggle Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
In this assignment, you will implement the game of BoggleT M , which will require you to (1) design and implement

a number of recursive algorithms and (2) think about various implementation strategies for the Boggle dictionary.

1 The Game of Boggle

Boggle is a word game played with sixteen cubes, where each side of each cube has one letter of the alphabet. The cubes are randomly arranged on a 4 × 4 grid, with one legal conﬁguration shown below:

The object of the game is to identify—in this grid of letters—words that satisfy the following conditions:

• The word must be at least four letters long.

• The path formed by the sequence of letters in the word must be connected horizontally, vertically, or diagonally.

For example, the above board contains the the word PEACE, which is legally connected as shown below.

The board does not contain the word PLACE, because the L and the P are not connected, and the board does not contain the word POPE, because the same P cannot be used more than once for a given word.

Points are scored based on the length of the word. Four-letter words are worth 1 point, ﬁve-letter words are worth

2 points, etc.

2 Your Boggle Game

You will create a Boggle game which randomly sets up a board. Your game will then allow a human to identify a list of words in the board, which your program will verify against some dictionary and for which your program will compute a score. When the human can think of no more words, your program will create a list of legal words that the human did not identify.

For example, if the human identiﬁed the following words for the above board:

lean

pace

bent

peel

pent

clan

clean

lent

1

EAALEPOBNQTTYHECEAALEPOBNQTTYHEC Your program would verify that each of these words was legal and would assign a score of 9 for the seven four-letter words and one ﬁve-letter word. Your program would then use a dictionary, whose words we will provide, to identify the following words (yeah, we didn’t know that hant and blent were words, either; neither does the Unix spellchecker):

celeb elan anele alec hale penal benthal bott toby topee

cape leant hant open

capelan capo leap lane blae neap than thae

cent lento blah thane

alee pele becap

cento peace blent toecap tope

For this wondrous list of words, your program would obtain a score of 56, thoroughly embarrassing the feeble

human player.

2.1

Initializing the Game

The game uses sixteen cubes, each with a particular set of letters on it. These letters have been chosen so that common letters are more likely to appear, and so that there is a good mix of consonants and vowels. You should initialize your cubes from the ﬁle, cubes.txt, which contains the following data:

LRYTTE VTHRWE EGHWNE SEOTIS ANAEEG IDSYTT OATTOW MTOICU AFPKFS XLDERI HCPOAS ENSIEU YLDEVR ZNRNHL NMIQHU OBBAOJ

Each line represents the six characters that will appear on the faces of a single cube. To initialize your game, you

should read this ﬁle and store the data in a data structure that represents the 16 cubes.

For each game, your program should randomly shufﬂe each cube and randomly distribute the cubes amongst the 4 × 4 grid. There are many ways to do this. You could lay down the cubes and start swapping them around, or you could pick cubes randomly and lay them down one at a time. Use any method that produces a good random permutation.

Your program will need to implement a simple dictionary that can read a large number of words (hundreds of thousands to millions of words) and store it in some judicious manner. The dictionary ﬁle is called words.txt, and it contains one word per line, with the words in ascending lexicographic order.

2.2 User Interface (UI)

We provide a curses-based1user interface to play Boggle.

When the game starts, the UI creates and displays a new scrambled Boggle board. It then accepts a word from the human player as input, checks the word for validity, and then computes a score for the word. If the word is valid, the interface indicates the location of the word on the board using Unicode arrows.

If the word is too short, not on the board, not a legal word, or is already used by the player, the UI indicates this to

the player. The player does not get credit for such words.

2

After the human indicates that they are done, the computer player gets to select all valid words that were not identiﬁed by the human. The program then displays the respective scores. After every game, the UI prompts the user for another game and acts accordingly.

The game is implemented in boggle.py in the top-level directory. It should run with python3 boggle.py. Use

python3 boggle.py -h for a full list of options.

2.3 The BoggleGame Interface

Everything that manages the mechanics of the game should be contained in a class that implements the BoggleGame interface. This interface provides all the necessary functions for implementing a basic generalized game of Boggle. The use of this interface completely separates the code that manages the game from the code that implements the UI.

class BoggleGame(abc.ABC):

class SearchTactic(enum.Enum): SEARCH_BOARD = enum.auto() SEARCH_DICT = enum.auto()

def new_game(

self, size: int, num_players: int, cubefile: str, dict: BoggleDictionary

) -&gt; None: … def get_board(self) -&gt; List[List[str]]: … def add_word(self, word: str, player: int) -&gt; int: … def get_last_added_word(self) -&gt; Optional[List[Tuple[int, int]]]: … def set_game(self, board: List[List[str]]) -&gt; None: … def get_all_words(self) -&gt; Collection[str]: … def set_search_tactic(self, tactic: SearchTactic) -&gt; None: … def get_scores(self) -&gt; List[int]: …

Implement your game engine as class GameManager in game_manager.py. For additional details, see boggle_game.py.

2.4 Dictionary Interface

To check for legal words, your program will need to search the dictionary, which you will implement. The methods in the BoggleDictionary interface, shown below, allow you to create a new dictionary and to insert words into it as an entire collection stored in a single ﬁle. The interface also speciﬁes methods to determine whether a string is found in the dictionary or whether it is a preﬁx of a word in the dictionary. These methods must be case-insensitive. Finally, the dictionary interface is an Iterable type, so you will need to implement the __iter__(self) method in your dictionary class. You will need to return an Iterator object from the dictionary class’s __iter__(self) method. For us to grade your assignment, you should ensure that your iterator terminates properly. For more information about the Iterable and Iterator types, see the following:

• The ofﬁcial documentation:

– https://docs.python.org/3/glossary.html#term-iterable – https://docs.python.org/3/library/stdtypes.html#typeiter

• Additional resources:

– https://wiki.python.org/moin/Iterator – https://www.programiz.com/python-programming/iterator

Although reading the ofﬁcial documentation is not always the easiest way to learn how to accomplish a particular task, it contains a great deal of technical information that is necessary to understand how the language works.

class BoggleDictionary(abc.ABC, Iterable):

def load_dictionary(self, filename: str) -&gt; None: … def is_prefix(self, prefix: str) -&gt; bool: … def contains(self, word: str) -&gt; bool: … def __iter__(self) -&gt; Iterator[str]: …

1https://en.wikipedia.org/wiki/Curses_(programming_library)

3

There are interesting design issues associated with the dictionary. You should strive to create the simplest possible dictionary that is reasonably efﬁcient. Your lookup operations should take O(log n) time or better. Be sure to justify your design decisions.

Because of the efﬁciency requirements, your dictionary should not just be an adaptor for some existing Python Standard Library class. It should instead be a new data structure. Your dictionary should be implemented as class GameDictionary in game_dictionary.py. For additional details, see boggle_dictionary.py.

2.5 Searching for Words

For the computer’s turn, your job is to ﬁnd all words that the human player missed. In this phase, the same conditions apply as for the human’s turn, plus the additional restriction that the computer cannot include any words that were already found by the human.

To do this, you will need to search the Boggle board for all words present. The get_all_words() method in the game interface should call one of the two following search strategies. We should be able to switch strategies via the set_search_tactic() method.

2.5.1 Board-Driven Search

The ﬁrst strategy is the obvious one: Recursively search the board for words beginning at each square on the board. As with any exponential search, you should prune the search as much as possible to speed things up. One important strategy is to recognize when you’re going down a dead end. For example, if you are searching for words that begin with the letters “ZX”, you can use the dictionary’s is_prefix() method (which you will implement), to determine that there are no English words that begin with this preﬁx and to recognize that your program can abandon this search path.

2.5.2 Dictionary-Driven Search

You should also implement a second strategy that iterates over all words in the Dictionary and checks whether these words can be found on the given board. There are various tricks you can play to improve the efﬁciency of this approach. We leave it to you to ﬁnd these tricks.

2.6 Correctness

The BoggleGame interface allows the game to be developed separately from user interface considerations. We should be able to use your game in our UI or test program without modiﬁcation. The interface also provides the set_game() method, which is extremely useful for debugging and testing your search functions.

Your user interface is allowed to assume traditional Boggle rules, although you might wish to make it somewhat

more general. Your game and dictionary should not assume these things.

3 What to Turn In

You only need to modify the ﬁles game_dictionary.py and game_manager.py. Use the Canvas website to submit a single ZIP ﬁle that contains your modiﬁed py_boggle directory.

Source code: Make sure all classes are in the correct ﬁles. Also make sure that your submission is using the correct directory structure. (The same directory structure provided by the starter code.)

4 Karma

If you have time on your hands, you might consider the question, “What board conﬁguration produces the highest score?” and you might consider some related questions: How would you identify such a board conﬁguration? Empir- ically? Theoretically? How many possible conﬁgurations are there?

Acknowledgments. This assignment was originally developed by Todd Feldman and enhanced by Julie Zelenski and Matt Alden. It was extensively modiﬁed by Walter Chang, with further improvements by Arthur Peters and Ashlie Martinez. Elvin Yang then converted this assignment to Python.

4
