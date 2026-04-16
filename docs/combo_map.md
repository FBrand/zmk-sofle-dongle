# ZMK Combo Map: Eyelash Sofle

This file serves as a quick reference for your vertical and horizontal combo matrix on **Layer 0 (BASE)**.

## 2D Visual Map

### Left Hand
```text
      ( 1 )   ( 2 )   ( 3 )   ( 4 )   ( 5 )
        |       |       |       |       |
      [ Q ]   [ W ]   [ E ]   [ R ]   [ T ] -- (ESC)
        +       +       +       +       +
      [ A ]   [ S ]   [ D ]   [ F ]   [ G ] -- (TAB)
                |       |       |
              ( ` )   ( = )   ( [ )
                +       +       +
              [ X ]   [ C ]   [ V ]   [ B ] -- (HARD)
```

### Right Hand
```text
      (DW ) -- [ Y ]   [ U ]   [ I ]   [ O ]   [ P ]
                 +       +       +       +       +
                 |     ( 7 )   ( 8 )   ( 9 )   ( 0 )
                 |
      ( - ) -- [ H ]   [ J ]   [ K ]   [ L ]   [ ; ] 
                         +       +       +
                         |       |       |
                       ( ] )   ( \ )   ( ' )
                         +       +       +
      (CW ) -- [ N ]   [ M ]   [ , ]   [ . ]   [ / ]
```

*(HARD = Hard Refresh `LC(LS(R))`, DW = Delete Word, CW = Caps Word)*

---

## 1. Numbers (Vertical Stacks)
| Result | Combo Keys |
| :--- | :--- |
| **1-5** | Q+A, W+S, E+D, R+F, T+G |
| **6-0** | Y+H, U+J, I+K, O+L, P+; |

## 2. Horizontal Shortcuts
| Result | Combo Keys | Row |
| :--- | :--- | :--- |
| **ESC** | R + T | Top Row |
| **TAB** | F + G | Home Row |
| **HARD Refresh**| V + B | Bottom Row |
| **Delete Word** | Y + U | Top Row (RH) |
| **- (Minus)** | H + J | Home Row (RH) |
| **Caps Word** | N + M | Bottom Row (RH) |

## 3. Verticals (Shifted/Remaining)
| Result | Combo Keys | Row Pair |
| :--- | :--- | :--- |
| **` (Grave)** | S + X | Home + Bottom |
| **= (Equal)** | D + C | Home + Bottom |
| **[ (L-Bracket)** | F + V | Home + Bottom |
| **] (R-Bracket)** | J + M | Home + Bottom |
| **\\ (Backslash)**| K + , | Home + Bottom |
| **' (Quote)** | L + . | Home + Bottom |

---

## Technical Details
- **Layers:** Strictly Layer 0 (Base)
- **Timing:** Standard 50ms timeout (ZMK Default)
- **Behaviors:** Non-destructive; will only trigger if key positions are hit simultaneously.
