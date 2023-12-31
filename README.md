# My First project in Java - Chess System

I am excited to present my first project in the world of Java programming - a chess system that serves as an exercise to enhance my skills. This project has been a stimulating journey, blending logic, creativity, and a touch of elegance in recreating the timeless game of chess.
###### Additionally, I am learning how to format markdown texts as part of the process.

## Checklists:
> **Step 1**
- [x] Class Position
- [x] OOP Topics:
  -  Encapsulation
  -  Constructors
  -  ToString(Object/overriding)
> **Step 2**
- [x] Classes Piece, Board
- [x] OOP Topics:
  -  Associations
  -  Encapsulation/Access Modifiers
- [x] Data Structures Topics:
  -  Matrix
> **Step 3**
- [x] Methods: Board.Piece(row, column) and Board.Piece(position)`
- [x] Enum Chess.Color
- [x] Class Chess.ChessPiece
- [x] Class Chess.ChessMatch
- [x] Class Application.UI
- [x] OOP Topics:
  -  Enumerations
  -  Encapsulation/Access Modifiers
  -  Inheritance
  -  Downcasting
  -  Static members
  -  Layers pattern
- [x] Data Structures Topics:
  -  Matrix
> **Step 4**
- [x] Method: Board.PlacePiece(piece, position)
- [x] Classes: Rook, King
- [x] Method: ChessMatch.InitialSetup 
- [x] OOP Topics:
  -  Inheritance
  -  Overriding
  -  Polymorphism (ToString)
> **Step 5**
- [x] Class BoardException
- [x] Methods: Board.PositionExists, Board.ThereIsAPiece
- [x] Implement defensive programming in Board methods
- [x] OOP Topics:
  -  Exceptions
  -  Constructors (a string must be informed to the exception)
> **Step 6**
- [x] Class ChessException
- [x] Class ChessPosition
- [x] Refactor ChessMatch.InitialSetup
- [x] OOP Topics:
  - Exceptions
  - Encapsulation
  - Constructors (a string must be informed to the exception)
  - Overriding
  - Static members
  - Layers pattern
> **Step 7**
- [x] Color in terminal:
  - IntelijIDEA terminal
- [x] Place more pieces on the board
- [x] Distinguish piece color in UI.PrintPiece method
> **Step 8**
- [x] Method Board.RemovePiece
- [x] Method UI.ReadChessPosition
- [x] Method ChessMatch.PerformChessMove
  - Method ChessMatch.MakeMove
  - Method ChessMatch.ValidateSourcePosition
- [x] Write basic logic on Program.cs
- [x] OOP Topics
  - Exceptions
  - Encapsulation
> **Step 9**
- [x] Cleaning screen using Java
- [x] ChessException
- [x] InputMismatchException
> **Step 10**
- [x] Methods in Piece
  - PossibleMoves [abstract]
  - PossibleMove
  - IsThereAnyPossibleMove
- [x] Basic PossibleMove implementation for Rook and King
- [x] Update ChessMatch.ValidadeSourcePosition
- [X] OOP Topics
  - Abstract method/class
  - Exceptions
> **Step 11**
- [x] Method ChessPiece.IsThereOpponentPiece(position) [protected]
- [x] Implement Rook.PossibleMoves
- [x] Method ChessMatch.ValidateTargetPosition
- [x] OOP Topics
  - Polymorphism
  - Encapsulation / access modifiers [protected]
  - Exceptions
> **Step 12**
- [x] Method ChessMatch.PossibleMoves
- [x] Method UI.PrintBoard [overload]
- [x] Refactor main program logic
- [x] OOP Topics:
  - Overloading
> **Step 13**
- [x] Method King.CanMove(position) [private]
- [x] Implement King.PossibleMoves
- [x] OOP Topics
  - Encapsulation
  - Polymorphism
> **Step 14**
- [x] Class ChessMatch
  - Properties Turn, CurrentPlayer [private set]
  - Method NextTurn [private]
  - Update PerformChessMove
  - Update ValidateSourcePosition
- [x] Method UI.PrintMatch
- OOP Topics
  - Encapsulation
  - Exceptions
> **Step 15**
- [x] Method UI.PrintCapturedPieces
- [x] Update UI.PrintMatch
- [x] Update Program logic
- [x] Lists in ChessMatch: _piecesOnTheBoard, _capturedPieces
  - Update constructor
  - Update PlaceNewPiece
  - Update MakeMove
- [X] OOP Topics
  - Encapsulation
  - Constructors
- [x] Data Structures Topics
  - List
> **Step 16**
- [x] Property ChessPiece.ChessPosition [get]
- [x] Class ChessMatch
  - Method UndoMove
  - Property Check [private set]
  - Method Opponent [private]
  - Method King (color) [private]
  - Method TestCheck
  - Update PerformChessMove
- [x] Update UI.PrintMatch
> **Step 17**
- [x] Class ChessMatch
  - Property Checkmate [private set]
  - Method TestCheckmate [private]
  - Update PerformChessMove
- [x] Update UI.PrintMatch
- [x] Update Program logic
> **Step 18**
- [x] Class ChessPiece
  - Property MoveCount [private set]
  - Method increaseMoveCount [protected]
  - Method decreaseMoveCount [protected]
- [x] Class ChessMatch
  - Update makeMove
  - Update undoMove
- [x] OOP Topics
  - Encapsulation
> **Step 19**
- [x] Pawn
  - Class Pawn
  - Update ChessMatch.InitialSetup
  - OOP Topics
    - Encapsulation
    - Inheritance
    - Polymorphism
- [x] Bishop
  - Class Bishop
  - Update ChessMatch.InitialSetup
  - OOP Topics
    - Encapsulation
    - Inheritance
    - Polymorphism
- [x] Knight
  - Class Knight
  - Update ChessMatch.InitialSetup
  - OOP Topics
    - Encapsulation
    - Inheritance
    - Polymorphism
- [x] Queen
  - Class Queen
  - Update ChessMatch.InitialSetup
  - OOP Topics
    - Encapsulation
    - Inheritance
    - Polymorphism
> **Step 20**
- [x] Special move - Castling
  - Update King
  - Update ChessMatch.MakeMove
  - Update ChessMatch.UndoMove
- [x] Special move - En Passant
  - Register a pawn which can be captured by en passant on next turn
    - Property ChessMatch.EnPassantVulnerable
    - Update ChessMatch.PerformChessMove
  - Update Pawn.PossibleMoves
  - Update ChessMatch.MakeMove
  - Update ChessMatch.UndoMove
  - Update ChessMatch.InitialSetup
- [x] Special move - Promotion
  - Property ChessMatch.Promoted
  - Update ChessMatch.PerformChessMove
  - Method ChessMatch.ReplacePromotedPiece
  - Update Program logic
###### I would like to express my gratitude to [Nélio Alves](https://www.udemy.com/course/java-curso-completo/#instructor-1) for his invaluable help throughout this Java trail. Thanks to his guidance, I have gained a solid understanding of object-oriented programming, exception handling, inheritance and polymorphism, enums, arrays, lists, and data structures.

