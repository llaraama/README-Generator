function generateMarkdown(answers) {
  return `# ${answers.title}

  ## Description: 
      ${answers.description}

  ## Table of Contents:

  ## Installation:
      ${answers.installation}
  ## Usage:
      ${answers.description}
  ## License:
      ${answers.license}
  ## Contributing:
      ${answers.contributors}
  ## Tests:
      ${answers.tests}
  ##Questions:


`;
}