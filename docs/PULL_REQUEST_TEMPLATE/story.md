version: 2
pull_request_templates:
  - name: "Story Template"
    branches:
      - "story/*"
    template: "./PULL_REQUEST_TEMPLATE/story.md"
  - name: "Fix Template"
    branches:
      - "fix/*"
    template: "./PULL_REQUEST_TEMPLATE/fix.md"