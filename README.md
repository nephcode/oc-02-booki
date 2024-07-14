![cover](https://kpkfzczpavanzocxzyta.supabase.co/storage/v1/object/pulic/oc-react/readme-header-oc-react-02.png)

# Booki

A pure HTML/CSS project for OpenClassrooms course AKA project 2

Online DEMO [https://oc02.youcodeuse.com](https://oc02.youcodeuse.com)
Online REPO [https://github.com/nephcode/oc-02-booki](https://github.com/nephcode/oc-02-booki)

## How to hot code instruction

2023/08/09 NephAcode. Fail ! That's going on Girls
I'm not Joking now, I'am so Tired to fix the code. Please follow the Debug part with my awnser. We are not in the road little runner. That's not cool . so i think we do restart and to make a perfect copycat

1. html integration
2. css without effect (no responsive)
3. css with all behaviors (focus, responsive...)

## Validation 2023/08/15
- `hn` filter section h3 to h2 (update css rule) **FIX**
- `text-decoration:none` in footer anchor **Fix** 

## Validation 2023/08/09

| TEST               | RESULT | COMMENT                                                              |
| ------------------ | ------ | -------------------------------------------------------------------- |
| HTML W3C Checker   | **OK** | Full OK 100% No errors or warnings to show.                          |
| CSS W3C            | **OK** | FULL OK 100%                                                         |
| CHROMIUM           | **OK** | Brave                                                                |
| FIREFOX            | **OK** | Firefox Developer Edition                                            |
| RESPONSIVE DESKTOP | **OK** | Over 1024 with margin at 1280 PX                                     |
| RESPONSIVE TABLET  | **OK** | Between 1024 to 768 in PX width                                      |
| RESPONSIVE MOBILE  | **OK** | Under 767 to 320 in PX ---> **FIX** FLEX to GRIP to FLEX under 320px |
| RESPONSIVE EXTREME | **OK** | Yes optimized column and gap for 2560px and 320px                    |

## Debug Responsive

### Global Css

- Class euro : bold > **FIX**
- Main Background : White > **FIX**
- Use var not #hex color > **FIX**

### Search and Filter

- `hn` filter section **FIX**
- Search optimize search button without display none > **FIX**
- Fix Adaptative > **FIX** (Grid to flex)
- Vertical Align infobubble with text > **FIX**

### Card

- Hover Click Zone **FIX**
- Card : Change the background-color to white > **FIX**
- Fix the hosting wrap over 1440px > **FIX**
- Merchandising Hosting Order on Mobile > **FIX**

### Footer

- Fix space between and align:start > **FIX**
- Text Decoration **Fix** 

```

Please open tickets to fix the bugs 😛 that a KANBAN


```

## Explain the project

The is a cool simulation with classic issues (**adaptative strange behaviors**). I thinked the projet for a future component implementation.

- I tried to use the minimal code in CSS and i keep my HTML code safe from _DIV invasion_
- Resolution 275px to cinema screen 2560px
- HTML and CSS files W3C are **OK**
- I used `#id` and `Cascade .class` with cascasde priority
- I use 2 sheet style `MAIN` and `TEMPLATE`.
- Logo `svg`
- Images optimized for speed loading with affinity photo `jpeg Ratio cropped`and `85% quality`
- Header nav link to `hosting`and `activities`
- Form no `display:none` Hack. I use `::before{content}` with _breackpoint_
- Form adapted to small phone under **320px**
- Filter use display **FLEX** and **GRID** with _breakpoint_
- **Filter Flex** for `Desktop Version`
- **Filter Flex** for `Tablet Version`
- **Filter Grid** for `Mobile Version` 2 Columns With breackpoint 767px > 320px
- **Filter Flex** under 320px with 1 column
- Little hack on family person with `font-size:xx-large` to match with others icons
- Info is an `svg`image with 2 rules of css to ajust align like template
- Main is full FLEX with breackpoints rules
- template use semantic `hn` and `section`
- `background-color` adaptation
- I choised Cascade on card to optimize behavoir for responsive and adaptative.
- Here, the main `.card` and others cascade top change the ratio img system `.lateral` and `.none`.
- Order section reverse on mobile **(just a flex-direction reverse )**
- Hosting .card order change _on mobile_ to respect the *web Merchandising* `nth-child:order(x)`
- Image ratio change with breackpoints
- Image respect initial ration
- Stars note position respect the figma
- `rem`, `vh`, `vw`, `px` use on the system
- `Calc()` could be use with specific rules
- Footer with `nav` and `ul li` classic flex direction breackpoint change

This system can be call by a future app.

![FooterNephcodePublic](https://kpkfzczpavanzocxzyta.supabase.co/storage/v1/object/public/nephcode-public/githubReadmeSkills.png)
\*By Nephacode - OpenClassrooms Project 2 - Booki, pure html css code - React Dev Stack
