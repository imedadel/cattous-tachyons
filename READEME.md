# Cattous-Tachyons

Tachyons theme to be used with [Cattous](https://github.com/ImedAdel/cattous).

## Variables

```JS
{
  breakpoints: [30, 60].map(n => n + "em"),
  space: [0, 0.25, 0.5, 1, 2, 4, 8, 16].map(n => n + "rem"),
  fontSizes: [0.75, 0.875, 1, 1.25, 1.5, 2.25, 3, 5, 6].map(n => n + "rem"),
  fontWeights: [100, 200, 300, 400, 500, 600, 700, 800, 900],
  lineHeights: {
    solid: 1,
    title: 1.25,
    copy: 1.5
  },
  letterSpacings: {
    normal: "normal",
    tracked: "0.1em",
    tight: "-0.05em",
    mega: "0.25em"
  },
  fonts: {
    serif: "georgia, times, serif",
    sansSerif:
      "-apple-system, BlinkMacSystemFont, 'avenir next', avenir, 'helvetica neue', helvetica, ubuntu, roboto, noto, 'segoe ui', arial, sans-serif",
    systemSanSerif: "sans-serif",
    systemSerif: "serif",
    code: "Consolas, monaco, monospace",
    courier: "'Courier Next', courier, monospace; ",
    helvetica: "'helvetica neue', helvetica, sans-serif",
    avenir: "'avenir next', avenir, sans-serif",
    athelas: "athelas, georgia, serif",
    georgia: "georgia, serif",
    times: "times, serif",
    bodoni: "'Bodoni MT', serif",
    calisto: "'Calisto MT', serif",
    garamond: "garamond, serif",
    baskerville: "baskerville, serif"
  },
  borders: [
    0,
    "1px solid",
    "2px solid",
    "4px solid",
    "8px solid",
    "16px solid",
    "32px solid"
  ],
  radii: {
    0: 0,
    1: "0.125rem",
    2: "0.25rem",
    3: "0.5rem",
    4: "1rem",
    pill: "9999px",
    p100: "100%"
  },
  width: {
    1: "1rem",
    2: "2rem",
    3: "4rem",
    4: "8rem",
    5: "16rem",
    p10: "10%",
    p20: "20%",
    p25: "25%",
    p30: "30%",
    p33: "33%",
    p34: "34%",
    p40: "40%",
    p50: "50%",
    p60: "60%",
    p70: "70%",
    p75: "75%",
    p80: "80%",
    p90: "90%",
    p100: "100%",
    third: "calc(100% / 3)",
    twoThirds: "calc(100% / 1.5)",
    auto: "auto"
  },
  heights: {
    1: "1rem",
    2: "2rem",
    3: "4rem",
    4: "8rem",
    5: "16rem",
    p25: "25%",
    p50: "50%",
    p75: "75%",
    p100: "100%",
    v25: "25vh",
    v50: "50vh",
    v75: "75vh",
    v100: "100vh",
    auto: "auto",
    inherit: "inherit"
  },
  maxWidths: {
    p100: "100%",
    1: "1rem",
    2: "2rem",
    3: "4rem",
    4: "8rem",
    5: "16rem",
    6: "32rem",
    7: "48rem",
    8: "64rem",
    9: "96rem",
    none: "none"
  },
  maxHeights: {
    p100: "100%",
    1: "1rem",
    2: "2rem",
    3: "4rem",
    4: "8rem",
    5: "16rem",
    6: "32rem",
    7: "48rem",
    8: "64rem",
    9: "96rem",
    none: "none"
  },
  minWidths: {
    1: "1rem",
    2: "2rem",
    3: "4rem",
    4: "8rem",
    5: "16rem",
    p10: "10%",
    p20: "20%",
    p25: "25%",
    p30: "30%",
    p33: "33%",
    p34: "34%",
    p40: "40%",
    p50: "50%",
    p60: "60%",
    p70: "70%",
    p75: "75%",
    p80: "80%",
    p90: "90%",
    p100: "100%",
    third: "calc(100% / 3)",
    twoThirds: "calc(100% / 1.5)",
    auto: "auto"
  },
  minHeights: {
    1: "1rem",
    2: "2rem",
    3: "4rem",
    4: "8rem",
    5: "16rem",
    p25: "25%",
    p50: "50%",
    p75: "75%",
    p100: "100%",
    v25: "25vh",
    v50: "50vh",
    v75: "75vh",
    v100: "100vh",
    auto: "auto",
    inherit: "inherit"
  },
  borderWidths: [0, 0.125, 0.25, 0.5, 1, 2].map(n => n + "rem"),
  borderStyles: {
    dotted: "dotted",
    dashed: "dashed",
    solid: "solid",
    none: "none"
  },
  shadows: {
    1: "0px 0px 4px 2px rgba( 0, 0, 0, 0.2 )",
    2: "0px 0px 8px 2px rgba( 0, 0, 0, 0.2 )",
    3: "2px 2px 4px 2px rgba( 0, 0, 0, 0.2 )",
    4: "2px 2px 8px 0px rgba( 0, 0, 0, 0.2 )",
    5: "4px 4px 8px 0px rgba( 0, 0, 0, 0.2 )"
  },
  zIndices: {
    0: 0,
    1: 1,
    2: 2,
    3: 3,
    4: 4,
    5: 5,
    999: 999,
    9999: 9999,
    max: 2147483647,
    inherit: "inherit",
    initial: "initial",
    unset: "unset"
  },
  hover: {
    dim: {
      opacity: 1,
      transition: "opacity .15s ease-in",
      "&:hover,&:focus": {
        opacity: 0.5,
        transition: "opacity .15s ease-in"
      },
      "&:active": {
        opacity: 0.8,
        transition: "opacity .15s ease-in"
      }
    },
    glow: {
      transition: "opacity .15s ease-in",
      "&:hover,&:focus": {
        opacity: 1,
        transition: "opacity .15s ease-in"
      }
    },
    underline: {
      "&:hover,&:focus": {
        textDecoration: "underline"
      }
    },
    grow: {
      "-moz-osx-font-smoothing": "grayscale",
      backfaceVisibility: "hidden",
      transform: "translateZ(0)",
      transition: "transform 0.25s ease-out",
      "&:hover,&:focus": {
        transform: "scale(1.05)"
      },
      "&:active": {
        transform: "scale(.90)"
      }
    },
    growLarge: {
      "-moz-osx-font-smoothing": "grayscale",
      backfaceVisibility: "hidden",
      transform: "translateZ(0)",
      transition: "transform 0.25s ease-out",
      "&:hover,&:focus": {
        transform: "scale(1.2)"
      },
      "&:active": {
        transform: "scale(.95)"
      }
    },
    pointer: {
      "&:hover": {
        cursor: "pointer"
      }
    },
    shadow: {
      "&::after": {
        content: "''",
        boxShadow: "0px 0px 16px 2px rgba( 0, 0, 0, .2 )",
        borderRadius: "inherit",
        opacity: "0",
        position: "absolute",
        top: "0",
        left: "0",
        width: "100%",
        height: "100%",
        zIndex: "-1",
        transition: "opacity 0.5s cubic-bezier(0.165, 0.84, 0.44, 1)"
      },
      "&:hover::after, &:focus::after": {
        opacity: 1
      }
    },
    bgAnimate: {
      transition: "background-color .15s ease-in-out",
      "&:hover,&:focus": {
        transition: "background-color .15s ease-in-out"
      }
    }
  },
  colors: {
    black: "#000",
    nearBlack: "#111",
    darkGray: "#333",
    midGray: "#555",
    gray: "#777",
    silver: "#999",
    lightSilver: "#aaa",
    moonGray: "#ccc",
    lightGray: "#eee",
    nearWhite: "#f4f4f4",
    white: "#fff",
    transparent: "transparent",
    black90: "rgba(0,0,0,.9)",
    black80: "rgba(0,0,0,.8)",
    black70: "rgba(0,0,0,.7)",
    black60: "rgba(0,0,0,.6)",
    black50: "rgba(0,0,0,.5)",
    black40: "rgba(0,0,0,.4)",
    black30: "rgba(0,0,0,.3)",
    black20: "rgba(0,0,0,.2)",
    black10: "rgba(0,0,0,.1)",
    black05: "rgba(0,0,0,.05)",
    black025: "rgba(0,0,0,.025)",
    black0125: "rgba(0,0,0,.0125)",
    white90: "rgba(255,255,255,.9)",
    white80: "rgba(255,255,255,.8)",
    white70: "rgba(255,255,255,.7)",
    white60: "rgba(255,255,255,.6)",
    white50: "rgba(255,255,255,.5)",
    white40: "rgba(255,255,255,.4)",
    white30: "rgba(255,255,255,.3)",
    white20: "rgba(255,255,255,.2)",
    white10: "rgba(255,255,255,.1)",
    white05: "rgba(255,255,255,.05)",
    white025: "rgba(255,255,255,.025)",
    white0125: "rgba(255,255,255,.0125)",
    darkRed: "#e7040f",
    red: "#ff4136",
    lightRed: "#ff725c",
    orange: "#ff6300",
    gold: "#ffb700",
    yellow: "#ffd700",
    lightYellow: "#fbf1a9",
    purple: "#5e2ca5",
    lightPurple: "#a463f2",
    darkPink: "#d5008f",
    hotPink: "#ff41b4",
    pink: "#ff80cc",
    lightPink: "#ffa3d7",
    darkGreen: "#137752",
    green: "#19a974",
    lightGreen: "#9eebcf",
    navy: "#001b44",
    darkBlue: "#00449e",
    blue: "#357edd",
    lightBlue: "#96ccff",
    lightestBlue: "#cdecff",
    washedBlue: "#f6fffe",
    washedGreen: "#e8fdf5",
    washedYellow: "#fffceb",
    washedRed: "#ffdfdf"
  },
  debug: {
    outlineChildren: {
      outline: "1px solid gold"
    },
    outlineChildrenWhite: {
      outline: "1px solid white"
    },
    outlineChildrenBlack: {
      outline: "1px solid black"
    },
    grid: {
      background:
        "transparent url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAgAAAAICAYAAADED76LAAAAFElEQVR4AWPAC97/9x0eCsAEPgwAVLshdpENIxcAAAAASUVORK5CYII=) repeat top left"
    },
    grid16: {
      background:
        "transparent url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAMklEQVR4AWOgCLz/b0epAa6UGuBOqQHOQHLUgFEDnAbcBZ4UGwDOkiCnkIhdgNgNxAYAiYlD+8sEuo8AAAAASUVORK5CYII=) repeat top left"
    },
    grid8Solid: {
      background:
        "white url(data:image/gif;base64,R0lGODdhCAAIAPEAAADw/wDx/////wAAACwAAAAACAAIAAACDZQvgaeb/lxbAIKA8y0AOw==) repeat top left"
    },
    grid16Solid: {
      background:
        "white url(data:image/gif;base64,R0lGODdhEAAQAPEAAADw/wDx/xXy/////ywAAAAAEAAQAAACIZyPKckYDQFsb6ZqD85jZ2+BkwiRFKehhqQCQgDHcgwEBQA7) repeat top left"
    }
  }
}
```