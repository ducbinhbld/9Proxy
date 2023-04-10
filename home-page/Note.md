************* Ghi chú những điều hay trong quá trình làm ****************


1. Cài đặt sass

npm i -g sass

sass ./sass/app.scss ./css/app.css --watch



2. Reponsive

- https://bizfly.vn/techblog/responsive-la-gi-cach-ung-dung-responsive-len-website.html


a. PC

- Có 2 tình huống:
    . TH 1: thông thường thì ko cần @media, cứ để nguyên vậy, ko làm gì cả
    . TH 2: Một số tình huống cần reponsive thì:
        @media screen and (min-width: 1280px)


b. Table

- Ipad Pro (1024px) and Ipad mini (768px)

==> @media screen and (max-width: 1023px)


c. Mobile

- Iphone 6/7/8 plus (414px)

==> @media screen and (max-width: 767px)


