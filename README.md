:root {
  --iris: #4d5ae5;
  --navyblue: #2e2f42;
  --cloud: #f4f4fd;
  --Silver: #c0c0c0;
  --slate: #434455;
  --cornflower: #e7e9fc;
  --white: #ffffff;
  --ocean: #404bbf;
}
h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin: 0;
}
ul {
  margin: 0;
  padding: 0;
}
cursor {
  pointer-events: painted;
}
/* .primary {
  color: var(--navyblue);
}
.secondary {
  color: var(--cloud);
}
.list-text:hover,
.list-text:focus {
  color: var(--iris);
}
cursor {
  pointer-events: painted;
}
.text-link:hover,
.text-link:focus {
  color: var(--iris);
}
.button-text:hover,
.button-text:focus {
  color: var(--white);
  background: #404bbf;
  border-color: #404bbf;
}
.button-subscribe:hover,
.button-subscribe:focus {
  background: #4d5ae5;
}
.professions {
  box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08),
    0px 1px 1px rgba(46, 47, 66, 0.16), 0px 2px 1px rgba(46, 47, 66, 0.08);
  border-radius: 0px 0px 4px 4px;
}
.social-link-footer-one:hover,
.social-link-footer-one:focus {
  background: #31d0aa;
}
.card-link:hover {
  box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08),
    0px 1px 1px rgba(46, 47, 66, 0.16), 0px 2px 1px rgba(46, 47, 66, 0.08);
  border-radius: 0px 0px 4px 4px;
}
.button-one:hover,
.button-one:focus {
  background: #404bbf;
}
.social-link:hover,
.social-link:focus {
  color: #404bbf;
}
.social-icon:hover,
.social-icon:focus {
  color: #404bbf;
  border-color: #404bbf;
}
.button-close:hover,
.button-close:focus {
  background: var(--iris);
  color: var(--white);
}
.professional-social-link:hover {
  background-color: var(--ocean);
}
.name:focus {
  border: 1px solid #4d5ae5;
  transition-property: border;
  transition-duration: 250ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  outline: none;
}
.name:focus + .modal-img-icon {
  fill: #4d5ae5;
  transition-property: fill;
  transition-duration: 250ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  outline: none;
}
.tel:focus {
  border: 1px solid #4d5ae5;
  transition-property: border;
  transition-duration: 250ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  outline: none;
}
.tel:focus + .modal-img-icon {
  fill: #4d5ae5;
  transition-property: fill;
  transition-duration: 250ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  outline: none;
}
.email:focus {
  border: 1px solid #4d5ae5;
  transition-property: border;
  transition-duration: 250ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  outline: none;
}
.email:focus + .modal-img-icon {
  fill: #4d5ae5;
  transition-property: fill;
  transition-duration: 250ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  outline: none;
}
.form-comment:focus {
  border: 1px solid #4d5ae5;
  transition-property: border;
  transition-duration: 250ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  outline: none;
}
.button-send:hover,
.button-send:focus {
  background: var(--iris);
}
.link-current::after {
  content: "";
  position: absolute;
  display: block;
  width: 100%;
  height: 4px;
  background: #404bbf;
  border-radius: 2px;
  left: 0;
  bottom: 0;
  color: #404bbf;
  margin-bottom: -1px;
}
.section-one {
  background: var(--navyblue);
  padding-top: 188px;
  padding-bottom: 188px;
  background-image: linear-gradient(
      rgba(46, 47, 66, 0.7),
      rgba(46, 47, 66, 0.7)
    ),
    url(../images/people-office\ 1.jpg);
  background-repeat: no-repeat;
  width: 1440px;
  margin: 0 auto;
}
.beckdrop {
  position: fixed;
  opacity: 1;
  left: 0;
  top: 0;
  z-index: 100;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.2);
  transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.beckdrop.is-hidden {
  opacity: 0;
  pointer-events: none;
}
.modal {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 408px;
  height: 576px;
  display: flex;
  flex-direction: column;
  padding: 40px;
  padding-right: 24px;
  padding-left: 24px;
  background-color: var(--white);
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14),
    0px 2px 1px rgba(0, 0, 0, 0.2);
  border-radius: 4px;
}
.button-close {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 24px;
  height: 24px;
  position: absolute;
  right: 24px;
  top: 24px;
  border-radius: 50%;
  background: transparent;
  border: 1px solid rgba(231, 233, 252, 1);
  cursor: pointer;
  background: #e7e9fc;
  color: #000;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.modal-img {
  fill: currentColor;
}
.name {
  width: 360px;
  height: 40px;
  background: #fcfcfc;
  border-radius: 4px;
  margin-top: 4px;
  margin-bottom: 8px;
  text-indent: 38px;
  border: 1px solid rgba(46, 47, 66, 0.2);
}
.tel {
  width: 360px;
  height: 40px;
  background: #fcfcfc;
  border-radius: 4px;
  border: 1px solid #2e2f42;
  margin-bottom: 8px;
  margin-top: 4px;
  text-indent: 38px;
  border: 1px solid rgba(46, 47, 66, 0.2);
}
.email {
  width: 360px;
  height: 40px;
  background: #fcfcfc;
  border-radius: 4px;
  margin-top: 4px;
  border: 1px solid #2e2f42;
  margin-bottom: 8px;
  text-indent: 38px;
  border: 1px solid rgba(46, 47, 66, 0.2);
}
.comment {
  width: 360px;
  height: 120px;
  left: 0px;
  top: 216px;
  border: 1px solid #2e2f42;
  border-radius: 4px;
  margin-bottom: 16px;
  border: 1px solid rgba(46, 47, 66, 0.2);
}
.modal-text {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 14px;
  letter-spacing: 0.04em;
  color: #8e8f99;
  padding-top: 8px;
  padding-bottom: 4px;
  position: relative;
}
.text-modal {
  width: 360px;
  height: 24px;
  left: 540px;
  top: 152px;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  text-align: center;
  letter-spacing: 0.02em;
  color: #2e2f42;
  padding-top: 24px;
  padding-bottom: 34px;
}
.modal-form-custom-checkbox{
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 16px;
  height: 16px;
  margin-left: 10px;
  margin-right: 10px;
  border: 2px solid var(--navyblue);
  margin-top: 16px;
}
.modal-form-checkbox:checked + .modal-form-custom-checkbox{
background: #404BBF;
border: 1px solid #404BBF;
border-radius: 2px;
}
.modal-form-checkbox:checked + .modal-form-custom-checkbox .modal-form-checkbox-icon{
  opacity: 1;
  fill: var(--iris);
}
.modal-form-option-span{
  font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 12px;
line-height: 14px;
letter-spacing: 0.04em;
color: #8E8F99;
}
.button-send {
  display: flex;
  flex-direction: row;
  margin: 0 auto;
  display: block;
  padding: 16px 32px;
  gap: 10px;
  width: 169px;
  height: 56px;
  background: var(--ocean);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
  border-radius: 4px;
  cursor: pointer;
  font-family: "Roboto";
  font-style: normal;
  align-items: center;
  text-align: center;
  color: #ffffff;
  border: none;
  margin-top: 24px;
  transition: background 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.modal-img-icon {
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  top: 45px;
  left: 19px;
  transform: translateY(-50%);
}
.form-comment {
  display: flex;
  justify-content: center;
  width: 360px;
  height: 120px;
  border: 1px solid rgba(46, 47, 66, 0.2);
  border-radius: 4px;
  padding-top: 8px;
  padding-left: 16px;
  margin-top: 4px;
  resize: none
}
.form-comment::placeholder {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 14px;
  letter-spacing: 0.04em;
  color: rgba(46, 47, 66, 0.4);
  opacity: 20;
}
.address {
  margin-left: auto;
}
.section-two {
  padding-top: 120px;
  padding-bottom: 120px;
}
.section-three {
  padding-bottom: 120px;
}
.section-four {
  background: var(--cloud);
  padding-top: 120px;
  padding-bottom: 120px;
}
.section-five {
  padding-top: 130px;
  padding-bottom: 120px;
}
.social-item {
  width: 168px;
  height: 88px;
}
.social-box {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 24px;
}
.social-icon {
  width: 168px;
  height: 88px;
  border: 1px solid #8e8f99;
  border-radius: 4px;
  fill: currentColor;
  transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.social-link {
  color: #8e8f99;
  transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.customers {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 1.1;
  text-align: center;
  letter-spacing: 0.02em;
  text-transform: capitalize;
  margin-bottom: 72px;
  color: #2e2f42;
}
.professions-social-list {
  display: flex;
  align-items: center;
  gap: 24px;
  justify-content: center;
  padding-top: 8px;
  padding-bottom: 32px;
  background-color: var(--white);
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.professional-social-link {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background-color: var(--iris);
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.rectangle-one {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 264px;
  height: 112px;
  background: #f4f4fd;
  border-radius: 4px;
  margin-bottom: 8px;
}
.social-icon-antenna {
  width: 64px;
  height: 64px;
}
.section-img {
  display: flex;
  column-gap: 24px;
  flex-wrap: wrap;
  margin-top: 72px;
  row-gap: 48px;
}
.section-portfolio {
  padding-top: 96px;
  padding-bottom: 120px;
}
.text {
  background: #ffffff;
  border: 1px solid #e7e9fc;
  padding-top: 32px;
  border-top: none;
  padding-left: 16px;
}
.list-professions {
  display: flex;
  gap: 24px;
}
.professions {
  box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08),
    0px 1px 1px rgba(46, 47, 66, 0.16), 0px 2px 1px rgba(46, 47, 66, 0.08);
  border-radius: 0px 0px 4px 4px;
}
.list-markers {
  list-style-type: none;
}
.footer {
  background: var(--navyblue);
  padding-top: 100px;
  padding-bottom: 100px;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.logo-primary-link {
  color: var(--cloud);
}
.logo-secondary-link {
  color: var(--iris);
}
body {
  font-family: "Roboto", sans-serif;
  color: var(--Silver);
  background: var(--white);
}
img {
  display: block;
}
header {
  border-bottom: 1px solid #e7e9fc;
}
.conteanir {
  width: 1158px;
  padding: 0 15px;
  margin: 0 auto;
}
header .conteanir {
  display: flex;
  align-items: center;
}
.site-nav {
  display: flex;
  gap: 40px;
  background: var(--white);
}
.logo-style {
  font-family: "Raleway";
  font-style: normal;
  font-weight: 800;
  font-size: 18px;
  line-height: 1.33;
  align-items: center;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: var(--iris);
  flex: none;
  order: 0;
  flex-grow: 0;
}
.logo {
  font-family: "Raleway";
  font-style: normal;
  font-weight: 800;
  font-size: 18px;
  line-height: 1.33;
  display: flex;
  align-items: center;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  text-decoration: none;
}
.site-nav-link {
  font-family: "Roboto";
  font-style: normal;
  width: 261px;
  font-weight: 500;
  font-size: 20px;
  line-height: 1.33;
  display: flex;
  text-align: center;
  gap: 40px;
}
.auth-nav-link {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.33;
  display: flex;
  gap: 40px;
}
.text-link {
  font-family: inherit;
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 1.33;
  letter-spacing: 0.02em;
  color: var(--slate);
  text-decoration: none;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.list-title-one {
  font-weight: 700;
  font-size: 56px;
  line-height: 1.07;
  letter-spacing: 0.02em;
  color: var(--white);
  text-align: center;
  width: 496px;
  margin: 0px auto;
  margin-bottom: 48px;
}
.title-What {
  font-weight: 700;
  font-size: 36px;
  line-height: 1.1;
  letter-spacing: 0.02em;
  text-transform: capitalize;
  color: var(--navyblue);
  text-align: center;
  margin-bottom: 72px;
}
.photo-one {
  flex-grow: 0;
  display: flex;
  gap: 24px;
  margin-top: 72px;
}
.title-Our {
  font-weight: 700;
  font-size: 36px;
  line-height: 1.1;
  letter-spacing: 0.02em;
  color: var(--navyblue);
  text-align: center;
}
.list-title-our-team {
  font-weight: 500;
  font-size: 20px;
  line-height: 1.33;
  letter-spacing: 0.02em;
  text-align: center;
  color: var(--navyblue);
  background: var(--white);
  padding-top: 32px;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.list-text-our-team {
  font-weight: 400;
  font-size: 16px;
  line-height: 1.33;
  color: var(--slate);
  display: flex;
  justify-content: center;
  background: var(--white);
  padding: 8px;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.button-filter {
  align-items: flex-start;
  justify-content: center;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  border-radius: 4px;
  flex: none;
  order: 1;
  flex-grow: 0;
  gap: 24px;
  margin-bottom: 72px;
}
.button-text {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.5;
  display: flex;
  align-items: center;
  text-align: center;
  letter-spacing: 0.04em;
  padding: 12px 24px;
  color: #4d5ae5;
  background: #f4f4fd;
  cursor: pointer;
  border: 1px solid #e7e9fc;
  border-radius: 4px;
  transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1),
    background 250ms cubic-bezier(0.4, 0, 0.2, 1),
    border-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.button-one {
  font-family: "Roboto";
  font-weight: 500;
  font-size: 16px;
  line-height: 1.33;
  padding: 16px 32px;
  color: var(--white);
  background: var(--iris);
  margin: 0 auto;
  display: block;
  border-radius: 4px;
  border: none;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
  cursor: pointer;
}
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  border: 0;
  white-space: nowrap;
  clip-path: inset(100%);
  clip: rect(0 0 0 0);
  overflow: hidden;
}
.list-title-studio {
  font-weight: 500;
  font-size: 20px;
  line-height: 1.33;
  color: var(--navyblue);
  letter-spacing: 0.02em;
  margin-bottom: 8px;
}
.list-text-studio-heder {
  position: relative;
  padding: 24px 0;
  display: inline-block;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.02em;
  color: var(--ocean);
  text-decoration: none;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.list-text-studio {
  font-weight: 400;
  font-size: 16px;
  line-height: 1.33;
  letter-spacing: 0.02em;
  color: var(--slate);
}
.list-title {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 24px;
  letter-spacing: 0.02em;
  color: #2e2f42;
  flex: none;
  order: 0;
  flex-grow: 0;
}
.list-text {
  position: relative;
  padding: 24px 0;
  display: inline-block;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.02em;
  color: #434455;
  text-decoration: none;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.list-text-portfolio {
  position: relative;
  padding: 24px 0;
  display: inline-block;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.02em;
  color: #434455;
  text-decoration: none;
}
.card-link {
  text-decoration: none;
  display: block;
  width: 360px;
  height: 420px;
}
.card-overlay {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.02em;
  color: #f4f4fd;
  background: #4d5ae5;
  mix-blend-mode: normal;
  padding: 20px;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  transform: translateY(100%);
  transition: transform 0.35s linear;
  overflow: scroll;
  padding: 40px 32px 164px 32px;
}
.text-wrap {
  position: relative;
  overflow: hidden;
}
.card-link:hover .card-overlay {
  transform: translateY(0);
  background: #4d5ae5;
}
.text-footer {
  line-height: 1.33;
  letter-spacing: 0.02em;
  color: var(--cornflower);
  width: 264px;
  margin-top: 17px;
}
.logo-footer {
  font-family: inherit;
  font-style: normal;
  font-weight: 800;
  font-size: 18px;
  line-height: 1.33;
  letter-spacing: 0.03em;
  color: var(--cloud);
  flex-direction: row;
  text-decoration: none;
}
.logo-primary-link {
  font-family: "Raleway", sans-serif;
  font-style: normal;
  font-weight: 800;
  font-size: 18px;
  line-height: 21px;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: var(--iris);
  transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.footer-box-one {
  display: flex;
  width: 1158px;
  padding: 0 15px;
  margin: 0 auto;
  color: var(--white);
  gap: 120px;
}
.social-link-footer {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 0px;
  gap: 16px;
  margin-top: 16px;
}
.social-link-footer-one {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.1);
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.social-box-footer {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 40px;
  height: 40px;
}
.social-media {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.02em;
  color: #ffffff;
}
.subscribe-media {
  display: flex;
  align-items: center;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.02em;
  color: #ffffff;
  margin-bottom: 16px;
}
.subscribe-link-footer {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 0px;
  gap: 16px;
  margin-top: 16px;
}
.button-subscribe {
  padding: 8px 24px;
  margin-left: 24px;
  background: var(--ocean);
  border-radius: 4px;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
  letter-spacing: 0.04em;
  color: #ffffff;
  border: none;
  cursor: pointer;
  transition: background 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.form-footer {
  display: flex;
  justify-content: center;
}
.subscribe-icon-footer {
  fill: #ffffff;
}
.email-footer {
  background: #2e2f42;
  border: 1px solid #ffffff;
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
  border-radius: 4px;
  width: 235px;
  height: 40px;
  padding-left: 16px;
  color: var(--white);
}
.email-footer::placeholder {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 24px;
  display: flex;
  align-items: center;
  letter-spacing: 0.04em;
  color: #ffffff;
} */
