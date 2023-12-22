# THUC HANH VOI CSS3

# HUU ICH

- dung `fallback color`: su dung gia tri thay the cho bien khi no ko ton tai

```css
:root {
  --color: red;
}
.list {
  color: var(--color, blue);
  /* khi --color khong ton tai thi se lay gia tri `blue` thay the */
}
```

## 1.SELECTORS

- toan tu `+` phan tu lien ke
- toan tu `~` phan tu cung cap
- toan tu `>` phan tu con trai/gai kkk

## 2.EM VS REM - ap dung theo font-size

- don vi `rem` tinh theo phan tu root (html)
- don vi `em` tinh theo phan tu do hoac phan tu chua no co

## 3. margin vs transform-translate ; top-left;

# DANH MUC THUC HANH 01

## DONE

- selectors & combinators (2parts)
- cach can center (2parts)
- pseudo :is vs :where
- khac nhau width giua auto vs 100% (thay doi khi su dung kich thuoc theo %, voi px khong anh huong)
  - auto -> phan tu se lay size theo ty le phan tu cha chua no
  - 100% -> 100%+(margin,padding) (transform-translate se tao ra 1 ban sao cua element va bien doi no -> tuong duong voi vc vi tri cu cua no hay la ban chinh cua no van ton tai o vi tri cu)
- tim hieu ve `:before & :after`
- width, min-width vs max-width

## RUNNING

- don vi em vs rem
- su khac nhau giua vw vs %
- bien trong css (bien trong scss sai $varName)
- ham calc() >>> thuc hanh bs sau flex
- responsive text
- intrinsic size
- currentColor
- so sanh `initial - unset - inherit`
- box-sizing (2parts)
- grid
- flex
- thuoc tinh ve position (thuc hanh dropdown sau flex)
- shape-outside
- ham radial-gradient

# DANH MUC THUC HANH 02

- clip-path polygon
- transform-origin
- transform:scale
- box-shadow
- responsive voi media screen
- responsive voi container Query
  ...

## THUC HANH SAU

- cach hoat dong cua LINEAR GRADIENT
- tao tam giac cho ribbon
- tim hieu Atomic css - tu build frameword css nhu tailwindcss
- hieu ung focus cho input
- curve backgound effects
- code Sticky table (basic)
- code 1 kute ghost
- slick slider
- tuy bien scrollbar
- path co ban
- border-gradient
