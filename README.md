stl-complexities
================

C++ STL container complexities with link references

<table border="1">
    <tbody>
        <tr>
            <td width="209" colspan="2">
                <p>
                    <b>Headers</b>
                </p>
                <p>
                    <b>ne</b>
                    = num elements passed to function
                    <br/>
                    <b>n</b>
                    = num elements in container
                </p>
            </td>
            <td width="66">
                <p align="center">
                    <b><a href="http://www.cplusplus.com/reference/vector/vector/">&lt;vector&gt;</a></b>
                </p>
                <p align="center">
                    (back insert)
                </p>
                <p align="center">
                    (forward, reversible, rand access)
                </p>
            </td>
            <td width="66">
                <p align="center">
                    <b><a href="http://www.cplusplus.com/reference/deque/deque/">&lt;deque&gt;</a></b>
                </p>
                <p align="center">
                    (back/front insert)
                </p>
                <p align="center">
                    (forward, reversible, rand access)
                </p>
            </td>
            <td width="66">
                <p align="center">
                    <b><a href="http://www.cplusplus.com/reference/list/list/">&lt;list&gt;</a></b>
                </p>
                <p align="center">
                    (back/front insert)
                </p>
                <p align="center">
                    (forward, reversible)
                </p>
            </td>
            <td width="189" valign="top">
                <p>
                    <b><a href="http://www.cplusplus.com/reference/set/set/">&lt;set&gt;</a> </b>
                </p>
                <p>
                    (forward)
                </p>
                <p>
                    (multiset for duplicate values)
                </p>
            </td>
            <td width="76">
                <p align="center">
                    <b><a href="http://www.cplusplus.com/reference/map/map/">&lt;map&gt;</a></b>
                    <br/>
                    map, multimap
                </p>
            </td>
        </tr>
        <tr>
            <td width="65" rowspan="3">
            </td>
            <td width="144">
                <p>
                    <i>
                        Constructor
                        <br/>
                    </i>
                    default: c;
                    <br/>
                    fill: c(ne, elem, alloc)
                    <br/>
                    range: c(inItA, iItB)
                    <br/>
                    copy: c(const c&amp;)
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::vector">vector</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::deque">deque</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::list">list</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::set">set</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::map">map</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    <i>destructor</i>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::~vector">~vector</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::~deque">~deque</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::~list">~list</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::~set">~set</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::~map">~map</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    operator=
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::operator=">operator=</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::operator=">operator=</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::operator=">operator=</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::operator=">operator=</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::operator=">operator=</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="65" rowspan="6">
                <p>
                    <b>capacity</b>
                </p>
            </td>
            <td width="144">
                <p>
                    size
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::size">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::size">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::size">O(1)</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::size">O(1)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::size">O(1)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    max_size [sys limit]
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::max_size">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::max_size">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::max_size">O(1)</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::max_size">O(1)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::max_size">O(1)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    empty
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::empty">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::empty">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::empty">O(1)</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::empty">O(1)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::empty">O(1)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    capacity  
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::capacity">O(1)</a>
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    reserve(space)
                    <br/>
                    Does not change size
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::reserve">O(n)</a>
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    resize(n, elem=def)
                    <br/>
                    Changes size
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::resize">O(n)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::resize">O(n)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::resize">O(n)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="65" rowspan="4">
                <p>
                    <b>element access</b>
                </p>
            </td>
            <td width="144">
                <p>
                    front
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::front">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::front">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::front">O(1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    back
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::back">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::back">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::back">O(1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    operator[i]
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::operator%5b%5d">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::operator%5b%5d">O(1)</a>
                </p>
            </td>
            <td width="66">
            </td>
            <td width="189">
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::operator%5b%5d">O(log n)</a>
                    (map)
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    at(i)
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::at">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::at">O(1)</a>
                </p>
            </td>
            <td width="66">
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="65" rowspan="12">
                <p>
                    <b>Modifiers</b>
                </p>
                <p>
                    <b></b>
                </p>
                <p>
                    <b></b>
                </p>
                <p>
                    (emplace C++11)
                </p>
            </td>
            <td width="144">
                <p>
                    assign(iterA, iterB): range
                    <br/>
                    assign(ne, val): fill
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::assign">
                        O(n)
                        <br/>
                        O(n)
                    </a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::assign">
                        O(ne)
                        <br/>
                        O(ne)
                    </a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::assign">
                        O(ne)
                        <br/>
                        O(ne)
                    </a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    insert(iter, val)
                    <br/>
                    insert(iter, ne, val)
                    <br/>
                    insert(iter, inItA, inItB)
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::insert">O(n)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::insert">O(1)</a>
                </p>
                <p>
                    <a href="http://www.cplusplus.com/deque::insert">
                        O(ne)
                        <br/>
                        O(ne)
                    </a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::insert">
                        O(1)
                        <br/>
                        O(ne)
                        <br/>
                        O(ne)
                    </a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::insert">pair&lt;it, bool&gt; insert(val): O(log n)</a>
                </p>
                <p>
                    <a href="http://www.cplusplus.com/set::insert">
                        iter insert(iter, val): O(1)
                        <br/>
                        inIt insert(inItA, inItB): O(ne log n)
                    </a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::insert">
                        O(log n)
                        <br/>
                        O(1)
                        <br/>
                        O(ne log n)
                    </a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    erase(iter)
                    <br/>
                    erase(iterA, iterB)
                    <br/>
                    size_t erase(val)
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::erase">
                        O(n)
                        <br/>
                        O(n)
                    </a>
                    <br/>
                    <br/>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::erase">
                        O(1)
                        <br/>
                        O(ne)
                    </a>
                    <br/>
                    <br/>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::erase">
                        O(1)
                        <br/>
                        O(ne)
                    </a>
                    <br/>
                    <br/>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::erase">
                        O(1)
                        <br/>
                        O(ne)
                        <br/>
                        O(log n)
                    </a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::erase">
                        O(1)
                        <br/>
                        O(ne)
                        <br/>
                        O(log n)
                    </a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    clear
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::clear">O(n)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::clear">O(n)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::clear">O(n)</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::clear">O(n)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::clear">O(n)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    swap(container &amp;)
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::swap">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::swap">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::swap">O(1)</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::swap">O(1)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::swap">O(1)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    push_back(val)
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::push_back">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::push_back">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::push_back">O(1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    pop_back
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::pop_back">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::pop_back">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::pop_back">O(1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    push_front(val)
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::push_front">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::push_front">O(1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    pop_front
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::pop_front">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::pop_front">O(1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    emplace(iter, ne,ele)
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::emplace">O(n)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::emplace">O(ne)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::emplace">O(ne)</a>
                </p>
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/set::emplace">O(log n)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/map::emplace">O(log n)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    emplace_back(elem)
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/vector::emplace_back">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::emplace_back">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::emplace_back">O(1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    emplace_front(elem)
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/deque::emplace_front">O(1)</a>
                </p>
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::emplace_front">O(1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="65" rowspan="7">
                <p>
                    <b>list operations</b>
                </p>
            </td>
            <td width="144">
                <p>
                    remove(val)
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::remove">O(n)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    remove_if(predicate)
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::remove_if">O(n)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    unique([binaryPred])
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::unique">O(n - 1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    merge(list &amp;m, [cmp])
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::merge">O(n + m -1)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    reverse
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::reverse">O(n)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    sort([cmp])
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::sort">O(n log n)</a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    splice(iter, list &amp;newLst)
                </p>
                <p>
                    splice(iter, list &amp;, inIter)
                </p>
                <p>
                    splice(it, list&amp;, inItA, inItB)
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
                <p>
                    <a href="http://www.cplusplus.com/list::splice">
                        O(1)
                        <br/>
                        O(1)
                        <br/>
                        O(ne)
                    </a>
                </p>
            </td>
            <td width="189">
            </td>
            <td width="76">
            </td>
        </tr>
        <tr>
            <td width="65" rowspan="4">
                <p>
                    <b>Associate containers operations</b>
                </p>
            </td>
            <td width="144">
                <p>
                    count
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/reference/set/set/count/">O(log n)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/reference/map/map/count/">O(log n)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    find
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/reference/set/set/find/">O(log n)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/reference/map/map/find/">O(log n)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    equal_range
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/reference/set/set/equal_range/">O(log n)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/reference/map/map/equal_range/">O(log n)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="144">
                <p>
                    lower_bound
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/reference/set/set/lower_bound/">O(log n)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/reference/map/map/lower_bound/">O(log n)</a>
                </p>
            </td>
        </tr>
        <tr>
            <td width="65">
            </td>
            <td width="144">
                <p>
                    upper_bound
                </p>
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="66">
            </td>
            <td width="189">
                <p>
                    <a href="http://www.cplusplus.com/reference/set/set/upper_bound/">O(log n)</a>
                </p>
            </td>
            <td width="76">
                <p>
                    <a href="http://www.cplusplus.com/reference/map/map/upper_bound/">O(log n)</a>
                </p>
            </td>
        </tr>
    </tbody>
</table>