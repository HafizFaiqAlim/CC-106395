#ifndef YY_YY_Y_TAB_H_INCLUDED
# define YY_YY_Y_TAB_H_INCLUDED
/* Debug traces.  */
#ifndef YYDEBUG
# define YYDEBUG 0
#endif
#if YYDEBUG
extern int yydebug;
#endif

/* Token type.  */
#ifndef YYTOKENTYPE
# define YYTOKENTYPE
  enum yytokentype
  {
    If = 258,
    Else = 259,
    While = 260,
    Class = 261,
    Extends = 262,
    Public = 263,
    Static = 264,
    Void = 265,
    Boolean = 266,
    Integer = 267,
    String = 268,
    True = 269,
    False = 270,
    This = 271,
    New = 272,
    Println = 273,
    Return = 274,
    ArrayLength = 275,
    Main = 276,
    Id = 277,
    Number = 278,
    And = 279
  };
#endif
/* Tokens.  */
#define If 258
#define Else 259
#define While 260
#define Class 261
#define Extends 262
#define Public 263
#define Static 264
#define Void 265
#define Boolean 266
#define Integer 267
#define String 268
#define True 269
#define False 270
#define This 271
#define New 272
#define Println 273
#define Return 274
#define ArrayLength 275
#define Main 276
#define Id 277
#define Number 278
#define And 279

/* Value type.  */
#if ! defined YYSTYPE && ! defined YYSTYPE_IS_DECLARED
typedef int YYSTYPE;
# define YYSTYPE_IS_TRIVIAL 1
# define YYSTYPE_IS_DECLARED 1
#endif


extern YYSTYPE yylval;

int yyparse (void);

#endif /* !YY_YY_Y_TAB_H_INCLUDED  */
