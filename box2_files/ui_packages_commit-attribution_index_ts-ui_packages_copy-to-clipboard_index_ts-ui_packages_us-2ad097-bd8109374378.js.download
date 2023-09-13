"use strict";(globalThis.webpackChunk=globalThis.webpackChunk||[]).push([["ui_packages_commit-attribution_index_ts-ui_packages_copy-to-clipboard_index_ts-ui_packages_us-2ad097"],{23663:(t,e,r)=>{r.d(e,{D:()=>j,C:()=>A});var o,a,i,n,l,s,p,d,c,u,h=r(85893),m=r(57294),f=r(78212),x=r(42483),g=r(73290),y=r(38490),b=r(97011);function v(t){return t.path?.startsWith("/apps/")??!1}function j({author:t,repo:e,avatarSize:r,sx:o={}}){if(!t)return null;let a=(0,h.jsx)(m.O,{"aria-label":`${t.login||"author"}`,src:t.avatarUrl,alt:`${t.login||"author"}`,sx:{mr:2},size:r,square:v(t)});return(0,h.jsxs)(x.Z,{sx:{display:"flex",flexDirection:"row",alignItems:"center",...o},"data-testid":"author-avatar",children:[t.path?(0,h.jsx)(g.Z,{href:t.path,"data-testid":"avatar-icon-link","data-hovercard-url":t.login?(0,f.zP)({owner:t.login}):void 0,children:a}):a,t.login?(0,h.jsx)(y.Z,{"aria-label":`commits by ${t.login}`,direction:"se",children:(0,h.jsx)(g.Z,{muted:!0,href:(0,f.OI)({repo:e,author:t.login}),"aria-label":`commits by ${t.login}`,sx:{fontWeight:600,whiteSpace:"nowrap",color:"fg.default","&:hover":{color:"fg.default",textDecoration:"underline"}},children:t.login})}):(0,h.jsx)(b.Z,{sx:{fontWeight:600,whiteSpace:"nowrap",color:"fg.default"},children:t.displayName})]})}try{(o=j).displayName||(o.displayName="AuthorAvatar")}catch{}var w=r(67294),N=r(50901),C=r(79902),k=r(66280);function $({authors:t,repo:e}){let r=t.length,[o,a]=(0,w.useState)(!1),i=(0,w.useRef)(null);return(0,h.jsxs)(h.Fragment,{children:[(0,h.jsxs)(g.Z,{as:"button","aria-label":`Show ${r} authors`,"data-testid":"authors-dialog-anchor",onClick:()=>{a(!0)},sx:{mx:1},ref:i,muted:!0,children:[r," ","people"]}),o&&(0,h.jsx)(k.V,{title:`${r} authors`,onClose:()=>{a(!1),setTimeout(()=>i.current?.focus(),25)},width:"medium",height:r>=12?"small":"auto",renderBody:()=>(0,h.jsx)(N.S,{sx:{overflowY:"auto",py:2},"data-testid":"contributor-dialog-list",children:t.map((t,r)=>(0,h.jsx)(S,{author:t,repo:e},`${t.login}_${r}`))})})]})}function S({author:t,repo:e}){return(0,h.jsxs)(N.S.LinkItem,{sx:{display:"flex",flexDirection:"row",fontSize:1,py:2,color:"fg.default","&:hover":{backgroundColor:"canvas.subtle"}},"data-testid":"contributor-dialog-row",href:(0,f.OI)({repo:e,author:t.login??""}),children:[(0,h.jsx)(m.O,{src:t.avatarUrl,alt:t.login??t.displayName,sx:{mr:2},"aria-hidden":"true",square:v(t)}),(0,h.jsx)(C.Z,{inline:!0,title:t.login??t.displayName??"",children:t.login??t.displayName})]})}try{(a=$).displayName||(a.displayName="AuthorsDialog")}catch{}try{(i=S).displayName||(i.displayName="AuthorRow")}catch{}var _=r(90836);function Z({authors:t,avatarSize:e}){return(0,h.jsx)(_.Z,{children:t.slice(0,5).map((t,r)=>(0,h.jsx)(m.O,{"data-testid":"commit-stack-avatar",src:t.avatarUrl,alt:t.login??t.displayName,"data-hovercard-url":(0,f.zP)({owner:t.login??""}),square:v(t),size:e},`${t.login}_${r}`))})}try{(n=Z).displayName||(n.displayName="CommitAuthorStack")}catch{}function P({author:t,repo:e,sx:r={}}){return t?(0,h.jsx)(x.Z,{sx:{display:"flex",flexDirection:"row",alignItems:"center",...r},"data-testid":"author-link",children:t.login?(0,h.jsx)(y.Z,{"aria-label":`commits by ${t.login}`,direction:"se",children:(0,h.jsx)(g.Z,{muted:!0,href:(0,f.OI)({repo:e,author:t.login}),"aria-label":`commits by ${t.login}`,sx:{fontWeight:600,whiteSpace:"nowrap",color:"fg.default","&:hover":{color:"fg.default",textDecoration:"underline"}},children:t.login})}):(0,h.jsx)(b.Z,{sx:{fontWeight:600,whiteSpace:"nowrap",color:"fg.default"},children:t.displayName})}):null}try{(l=P).displayName||(l.displayName="AuthorLink")}catch{}function z({author:t,repo:e,avatarSize:r}){return(0,h.jsx)(j,{author:t,repo:e,sx:{px:1},avatarSize:r})}function U({author:t,committer:e,repo:r,avatarSize:o}){return(0,h.jsxs)(h.Fragment,{children:[(0,h.jsx)(Z,{authors:[t,e],avatarSize:o}),(0,h.jsx)(P,{author:t,repo:r,sx:{px:1}})]})}function R({authors:t,repo:e,avatarSize:r}){return(0,h.jsxs)(h.Fragment,{children:[(0,h.jsx)(Z,{authors:t,avatarSize:r}),t.map((r,o)=>(0,h.jsxs)(w.Fragment,{children:[(0,h.jsx)(P,{author:r,repo:e,sx:{px:1}}),o!==t.length-1&&" and "]},`${r.login}_${o}`))]})}function T({authors:t,repo:e,avatarSize:r}){return(0,h.jsxs)(h.Fragment,{children:[(0,h.jsx)(Z,{authors:t,avatarSize:r}),(0,h.jsx)($,{authors:t,repo:e})]})}function A({authors:t,committer:e,committerAttribution:r,repo:o,avatarSize:a,includeVerbs:i=!0}){let n=1===t.length&&!r,l=1===t.length&&r,s=2===t.length&&!r;return(0,h.jsxs)(x.Z,{sx:{display:"flex",flexDirection:"row",alignItems:"center"},children:[n&&(0,h.jsx)(z,{author:t[0],repo:o,avatarSize:a}),l&&(0,h.jsx)(U,{author:t[0],committer:e,repo:o,avatarSize:a}),s&&(0,h.jsx)(R,{authors:t,repo:o,avatarSize:a}),!n&&!l&&!s&&(0,h.jsx)(T,{authors:t,repo:o,avatarSize:a}),r?(0,h.jsxs)(h.Fragment,{children:[(0,h.jsx)("span",{children:i?"authored and":"and"}),(0,h.jsx)(P,{author:e,repo:o,sx:{px:1}}),(0,h.jsx)("span",{children:i&&"committed"})]}):(0,h.jsx)("span",{children:i&&"committed"})]})}try{(s=z).displayName||(s.displayName="SingleAuthor")}catch{}try{(p=U).displayName||(p.displayName="AuthorAndCommitter")}catch{}try{(d=R).displayName||(d.displayName="TwoAuthors")}catch{}try{(c=T).displayName||(c.displayName="MultipleAuthors")}catch{}try{(u=A).displayName||(u.displayName="CommitAttribution")}catch{}},68912:(t,e,r)=>{r.d(e,{m:()=>x,z:()=>m});var o,a,i=r(85893),n=r(37169),l=r(85529),s=r(38490),p=r(42483),d=r(50919),c=r(67294);function u(t){let e=document.createElement("pre");return e.style.width="1px",e.style.height="1px",e.style.position="fixed",e.style.top="5px",e.textContent=t,e}function h(t){if("clipboard"in navigator)return navigator.clipboard.writeText(t.textContent||"");let e=getSelection();if(null==e)return Promise.reject(Error());e.removeAllRanges();let r=document.createRange();return r.selectNodeContents(t),e.addRange(r),document.execCommand("copy"),e.removeAllRanges(),Promise.resolve()}function m(t){if("clipboard"in navigator)return navigator.clipboard.writeText(t);let e=document.body;if(!e)return Promise.reject(Error());let r=u(t);return e.appendChild(r),h(r),e.removeChild(r),Promise.resolve()}function f({sx:t,tooltipProps:e}){return(0,i.jsx)(s.Z,{"aria-label":"Copied!",sx:t,...e,children:(0,i.jsx)(p.Z,{as:"span",sx:{display:"inline-block",color:"success.fg",p:1,mr:1},children:(0,i.jsx)(l.CheckIcon,{})})})}function x({icon:t=l.CopyIcon,size:e="medium",onCopy:r,sx:o,textToCopy:a,tooltipProps:p,confirmationComponent:u=(0,i.jsx)(f,{sx:o,tooltipProps:p}),ariaLabel:h,accessibleButton:x}){let[g,y]=c.useState(!1),b=(0,n.Z)(),v=()=>{y(!0),m(a),r?.(),setTimeout(()=>b()&&y(!1),2e3)},j=h??`Copy ${a} to clipboard`;return g?(0,i.jsx)(i.Fragment,{children:u}):(0,i.jsx)(s.Z,{"aria-label":j,...p,children:(0,i.jsx)(d.h,{"aria-label":j,icon:t,variant:"invisible",size:e,tabIndex:!1===x?-1:0,sx:{...o},onClick:v})})}try{(o=f).displayName||(o.displayName="CopyConfirmationCheck")}catch{}try{(a=x).displayName||(a.displayName="CopyToClipboardButton")}catch{}},95628:(t,e,r)=>{r.d(e,{M:()=>i});let o=t=>{let e=getComputedStyle(t,null);return["overflow","overflow-y","overflow-x"].some(t=>{let r=e.getPropertyValue(t);return"auto"===r||"scroll"===r})},a=(t,e)=>t&&null!==t.parentNode?a(t.parentNode,e.concat([t])):e;function i(t){if(!(t instanceof HTMLElement||t instanceof SVGElement))return;let e=a(t.parentNode,[]);for(let t of e)if((t instanceof HTMLElement||t instanceof SVGElement)&&o(t))return t;return document.scrollingElement||document.documentElement}},78806:(t,e,r)=>{r.d(e,{Z:()=>a});let o=(t,e)=>{let r=new URL(t,window.location.origin),o=new URL(e,window.location.origin),a=o.href.includes("#");return a&&r.host===o.host&&r.pathname===o.pathname&&r.search===o.search},a=o},37169:(t,e,r)=>{r.d(e,{Z:()=>i});var o=r(78249),a=r(67294);function i(){let t=(0,a.useRef)(!1),e=(0,a.useCallback)(()=>t.current,[]);return(0,o.g)(()=>(t.current=!0,()=>{t.current=!1}),[]),e}},68203:(t,e,r)=>{r.d(e,{s:()=>p});var o=r(67294),a=r(89250),i=r(12599),n=r(78806),l=r(45055),s=r(68202);let p=()=>{let{routes:t,history:e}=o.useContext(l.I),p=(0,a.s0)();return o.useCallback((o,a)=>{let l=(0,i.i3)(o).pathname,d=!(0,i.fp)(t,l);if(d){let t=e.createHref(o);(async()=>{let{softNavigate:e}=await Promise.all([r.e("vendors-node_modules_github_turbo_dist_turbo_es2017-esm_js"),r.e("ui_packages_soft-navigate_soft-navigate_ts")]).then(r.bind(r,75198));e(t)})()}else{(0,n.Z)(location.href,o.toString())||(0,s.LD)("react"),p(o,a);let{turbo:t,...e}=window.history.state;window.history.replaceState({...e,skipTurbo:!0},"",location.href)}},[e,p,t])}},32769:(t,e,r)=>{r.d(e,{H:()=>p,d:()=>s});var o,a,i=r(85893),n=r(67294);let l=n.createContext({});function s({repository:t,children:e}){return(0,i.jsxs)(l.Provider,{value:t,children:[" ",e," "]})}function p(){return n.useContext(l)}try{(o=l).displayName||(o.displayName="CurrentRepositoryContext")}catch{}try{(a=s).displayName||(a.displayName="CurrentRepositoryProvider")}catch{}},57294:(t,e,r)=>{r.d(e,{O:()=>s});var o,a=r(85893),i=r(67294),n=r(26012),l=r(86283);let s=(0,i.forwardRef)(function({src:t,size:e=20,...r},o){let s=(0,i.useMemo)(()=>{let r=new URL(t,l.jX.origin);return r.searchParams.has("size")||r.searchParams.has("s")||r.searchParams.set("size",String(2*Number(e))),r.toString()},[t,e]);return(0,a.jsx)(n.Z,{ref:o,src:s,size:e,"data-testid":"github-avatar",...r})});try{(o=s).displayName||(o.displayName="GitHubAvatar")}catch{}},45222:(t,e,r)=>{r.d(e,{h:()=>u});var o,a=r(85893),i=r(42379),n=r(15173),l=r(41905),s=r(86010),p=r(67294),d=r(15388);let c=d.ZP.span`
  &::before {
    position: absolute;
    z-index: 1000001;
    display: none;
    width: 0px;
    height: 0px;
    color: ${(0,i.U2)("colors.neutral.emphasisPlus")};
    pointer-events: none;
    content: '';
    border: 6px solid transparent;
    opacity: 0;
  }
  &::after {
    position: absolute;
    z-index: 1000000;
    display: none;
    padding: 0.5em 0.75em;
    font: normal normal 11px/1.5 ${(0,i.U2)("fonts.normal")};
    -webkit-font-smoothing: subpixel-antialiased;
    color: ${(0,i.U2)("colors.fg.onEmphasis")};
    text-align: center;
    text-decoration: none;
    text-shadow: none;
    text-transform: none;
    letter-spacing: normal;
    word-wrap: break-word;
    white-space: pre;
    pointer-events: none;
    content: attr(aria-label);
    background: ${(0,i.U2)("colors.neutral.emphasisPlus")};
    border-radius: ${(0,i.U2)("radii.1")};
    opacity: 0;
  }
  /* delay animation for tooltip */
  @keyframes tooltip-appear {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
  &.tooltipped-open,
  &:hover,
  &:active,
  &:focus {
    &::before,
    &::after {
      display: inline-block;
      text-decoration: none;
      animation-name: tooltip-appear;
      animation-duration: 0.1s;
      animation-fill-mode: forwards;
      animation-timing-function: ease-in;
      animation-delay: 0.4s;
    }
  }

  &.tooltipped-no-delay.tooltipped-open,
  &.tooltipped-no-delay:hover,
  &.tooltipped-no-delay:active,
  &.tooltipped-no-delay:focus {
    &::before,
    &::after {
      animation-delay: 0s;
    }
  }

  /* Tooltipped south */
  &.tooltipped-s,
  &.tooltipped-se,
  &.tooltipped-sw {
    &::after {
      top: 100%;
      right: 50%;
      margin-top: 6px;
    }
    &::before {
      top: auto;
      right: 50%;
      bottom: -7px;
      margin-right: -6px;
      border-bottom-color: ${(0,i.U2)("colors.neutral.emphasisPlus")};
    }
  }
  &.tooltipped-se {
    &::after {
      right: auto;
      left: 50%;
      margin-left: -${(0,i.U2)("space.3")};
    }
  }
  &.tooltipped-sw::after {
    margin-right: -${(0,i.U2)("space.3")};
  }
  /* Tooltips above the object */
  &.tooltipped-n,
  &.tooltipped-ne,
  &.tooltipped-nw {
    &::after {
      right: 50%;
      bottom: 100%;
      margin-bottom: 6px;
    }
    &::before {
      top: -7px;
      right: 50%;
      bottom: auto;
      margin-right: -6px;
      border-top-color: ${(0,i.U2)("colors.neutral.emphasisPlus")};
    }
  }
  &.tooltipped-ne {
    &::after {
      right: auto;
      left: 50%;
      margin-left: -${(0,i.U2)("space.3")};
    }
  }
  &.tooltipped-nw::after {
    margin-right: -${(0,i.U2)("space.3")};
  }
  /* Move the tooltip body to the center of the object. */
  &.tooltipped-s::after,
  &.tooltipped-n::after {
    transform: translateX(50%);
  }
  /* Tooltipped to the left */
  &.tooltipped-w {
    &::after {
      right: 100%;
      bottom: 50%;
      margin-right: 6px;
      transform: translateY(50%);
    }
    &::before {
      top: 50%;
      bottom: 50%;
      left: -7px;
      margin-top: -6px;
      border-left-color: ${(0,i.U2)("colors.neutral.emphasisPlus")};
    }
  }
  /* tooltipped to the right */
  &.tooltipped-e {
    &::after {
      bottom: 50%;
      left: 100%;
      margin-left: 6px;
      transform: translateY(50%);
    }
    &::before {
      top: 50%;
      right: -7px;
      bottom: 50%;
      margin-top: -6px;
      border-right-color: ${(0,i.U2)("colors.neutral.emphasisPlus")};
    }
  }
  &.tooltipped-align-right-2::after {
    right: 0;
    margin-right: 0;
  }
  &.tooltipped-align-right-2::before {
    right: 15px;
  }
  &.tooltipped-align-left-2::after {
    left: 0;
    margin-left: 0;
  }
  &.tooltipped-align-left-2::before {
    left: 10px;
  }
  ${n.Z};
`,u=(0,p.forwardRef)(function({direction:t="n",className:e,text:r,noDelay:o,align:i,wrap:n,open:p=!1,portalProps:d={},...u},h){let m=(0,s.W)(e,`tooltipped-${t}`,i&&`tooltipped-align-${i}-2`,o&&"tooltipped-no-delay",n&&"tooltipped-multiline",p&&"tooltipped-open");return(0,a.jsx)(l.h,{...d,children:(0,a.jsx)(c,{ref:h,role:"tooltip","aria-label":r,...u,sx:{position:"fixed",zIndex:1,...u.sx},className:m})})});try{(o=u).displayName||(o.displayName="ControlledTooltip")}catch{}},52793:(t,e,r)=>{r.d(e,{u:()=>p});var o,a=r(85893),i=r(48030),n=r(67294),l=r(45222),s=r(95628);let p=(0,n.forwardRef)(function({contentRef:t,open:e,anchoredPositionAlignment:r,anchorSide:o,anchorOffset:p,alignmentOffset:d,allowOutOfBounds:c,...u},h){let m=(0,n.useRef)(null);(0,n.useImperativeHandle)(h,()=>m.current);let f=(0,n.useRef)({left:0,top:0}),x=(0,n.useSyncExternalStore)((0,n.useCallback)(r=>{if(!m.current||!t.current||!e)return()=>void 0;let o=(0,s.M)(t.current);return o?.addEventListener("scroll",r),()=>{o?.removeEventListener("scroll",r)}},[t,e]),(0,n.useCallback)(()=>{if(!m.current||!t.current)return f.current;let e=(0,i.N)(m.current,t.current,{align:r??"center",side:o??"outside-top",alignmentOffset:d??0,anchorOffset:p??0,allowOutOfBounds:c});return(e.left!==f.current.left||e.top!==f.current.top)&&(f.current=e),f.current},[t,d,p,r,o,c]));return(0,a.jsx)(l.h,{...u,ref:m,open:e,style:{position:"absolute",...x,...u.style}})});try{(o=p).displayName||(o.displayName="PortalTooltip")}catch{}},60348:(t,e,r)=>{r.d(e,{r:()=>p});var o=r(85893),a=r(67294),i=r(12599),n=r(79655),l=r(45055),s=r(86283);let p=a.forwardRef(({to:t,reloadDocument:e,...r},p)=>{let{routes:d}=a.useContext(l.I),c=(0,i.i3)(t,s.jX.pathname).pathname;return e=e??!(0,i.fp)(d,c),(0,o.jsx)(n.rU,{to:t,...r,reloadDocument:e,ref:p})});p.displayName="Link"}}]);
//# sourceMappingURL=ui_packages_commit-attribution_index_ts-ui_packages_copy-to-clipboard_index_ts-ui_packages_us-2ad097-200b7637c8f8.js.map