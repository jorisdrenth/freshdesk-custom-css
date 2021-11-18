Freshdesk custom css snippets
=============================

This repo contains some css snippets which can be used with the Freshdesk support panel for agents. I use these for myself, but thought it might be of interest for more people using this software.

Use your preferred custom css browser plugin to add these for your Freshdesk URL.

Chat-like interface for tickets
--------------------------
Outline the customer's messages left and yours on the right. Specially usefull when dealing with long tickets.

```css
.ticket-details__item.ticket-details__requestor {
    width:70%;
    margin-left: 0;
}

.ticket-details__item {
    width:70%;
    margin-left: 30%;
    border: 1px solid #d4dce3;
}
```

Disable flashing red circle
------------------------
The red circle showing other users who are viewing or writing in a ticket can be very distracting. Use this snippet to disable the flashing, but still show the eye or pencil icon:

```css
.agent_collision .flip-front {
    animation-name: bye !important;
}
```
