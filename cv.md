<img src="/public/avatar.png" alt="photo"/>

# Full Name
Korolev Sergey

# Contact Information
<span style="float:right;padding:6px"> 
  serhio@gmail.com <br> mobile: +995 555100700
</span>

# Brief Self-Introduction
## Goals
My goal is professional growth.
## Strengts
I am purposeful and achieve goals.
## Working projects
Studies, pet project.
## Interests
I like to learn and acquire new skills.


# Skills
## Languages
JavaScript, HTML/CSS, Python, C#, SQL (Postgres), 
## Frameworks
React, Node.JS, Flask, Joomla, Bitrix
## Developer Tools
Git, Docker, Webstorm
## Libraries
React Route, Regex


# Code Examples
function CityList() {
  const { cities, isLoading } = useCities();

  if (isLoading) return <Spinner />;
  if (!cities.length) 
    return (
      <Message message="Add your firs cuty by clicking on a city on the map" />
    );

    
  return (
    <div>
      <ul className={styles.cityList}>
        {cities.map((city, id) => (
          <CityItem city={city} key={id} />
        ))}
      </ul>
    </div>
  );
}

export default CityList;



# Working Experience/Projects 

## ReactJS-samurai-way (2023/10 - 2023/12) 

* [Social chat app](https://github.com/serhio1212/ReactJS-samurai-way-1)

## The Ultimate React Course 2023 React, Redux & More(EN) (2024/06 - 2024/10) 

* [Worldwise app](https://github.com/serhio1212/Owner-avatar-The-Ultimate-React-Course-2023-worldwise)
* [Calendar app](https://github.com/serhio1212/The-Ultimate-React-Course-2023-calend)
* [Spoiler app](https://github.com/serhio1212/The-Ultimate-React-Course-2023-spoiler)


# Education & Qualifications

* EPAM Front-end Basic (2024/05 - 2024/07)
* Baltic Fishing Fleet State Academ / Automated Information Processing and Control Systems (2007/06 - 2011/07)
* Baltic Fishing Fleet State Academy / ASP LINUX 11.2 Administration (2006/05 - 2006/08)

# Soft Skills 

* Languages: English (A2 - B1)

