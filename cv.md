# Stanislav Narckevich

## Contact Info

+ Email: [sn21111997@gmail.com](sn21111997@gmail.com)
+ Github: [https://github.com/StanislavNarckevich](https://github.com/StanislavNarckevich)
+ LinkedIn: [https://www.linkedin.com/in/stanislav-narkevich](https://www.linkedin.com/in/stanislav-narkevich)
+ Skype: sn21111997
## Summary

My name is Stas, I have been studying web development for about a year.
At the moment I studied html, css (bootstrap 4, flexbox, grid), scss, javascript (ES6), git, gulp, a little jQuerry, and basic knowledge of ReactJS, I have experience in creating a website on WordPress.
At the moment I am improving my knowledge of React
I am constantly working to develop my skills. I want to develop professionally and improve my skills


## Skills

- HTML
- CSS/SCSS
- JavaScript
- Git
- Gulp
- ES6
- jQuery
- WordPress
- ReactJS 


## Code examples

Building Todo-List on ReactJS
``` javascript
  render() {
    const { items, filter, search } = this.state;
    const doneCount = items.filter((item) => item.done).length;
    const toDoCount = items.length - doneCount;
    const visibleItems = this.searchItems(this.filterItems(items, filter), search);

    return (
      <div className="todo-app">
        <AppHeader toDo={toDoCount} done={doneCount}/>

        <div className="search-panel d-flex">
          <SearchPanel
            onSearchChange={this.onSearchChange}/>

          <ItemStatusFilter
            filter={filter}
            onFilterChange={this.onFilterChange} />
        </div>

        <TodoList
          items={ visibleItems }
          onToggleImportant={this.onToggleImportant}
          onToggleDone={this.onToggleDone}
          onDelete={this.onDelete} />
```


## Experience

I have experience in developing a website for cms WordPress, I took part in a training workshop which, I made an application for finding TV shows in javascrript. I was written todo-list on ReactJS

## Education

Self-education
