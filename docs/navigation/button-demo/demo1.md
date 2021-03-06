```hbs template
<EuiTitle @size="m">
  Button
</EuiTitle>
<EuiSpacer @size="s" />
<div class="euiFlexGroup euiFlexGroup--gutterSmall euiFlexGroup--alignItemsCenter">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}}>
      Primary
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @fill={{true}}>
      Filled
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @size="s">
      Small
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @size="s" @fill={{true}}>
      Small Filled
    </EuiButton>
  </div>
</div>
<div class="euiFlexGroup euiFlexGroup--gutterSmall euiFlexGroup--alignItemsCenter">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @color="secondary">
      Primary
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @fill={{true}} @color="secondary">
      Filled
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @size="s" @color="secondary">
      Small
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @size="s" @fill={{true}} @color="secondary">
      Small Filled
    </EuiButton>
  </div>
</div>
<div class="euiFlexGroup euiFlexGroup--gutterSmall euiFlexGroup--alignItemsCenter">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @color="warning">
      Primary
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @fill={{true}} @color="warning">
      Filled
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @size="s" @color="warning">
      Small
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @size="s" @fill={{true}} @color="warning">
      Small Filled
    </EuiButton>
  </div>
</div>
<div class="euiFlexGroup euiFlexGroup--gutterSmall euiFlexGroup--alignItemsCenter">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @color="danger">
      Primary
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @fill={{true}} @color="danger">
      Filled
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @size="s" @color="danger">
      Small
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{this.clickedButton}} @size="s" @fill={{true}} @color="danger">
      Small Filled
    </EuiButton>
  </div>
</div>
<div class="euiFlexGroup euiFlexGroup--gutterSmall euiFlexGroup--alignItemsCenter">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @isDisabled={{true}} @onClick={{this.clickedButton}} @color="danger">
      Primary
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @isDisabled={{true}} @onClick={{this.clickedButton}} @fill={{true}} @color="danger">
      Filled
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @isDisabled={{true}} @onClick={{this.clickedButton}} @size="s" @color="danger">
      Small
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton
      @isDisabled={{true}}
      @onClick={{this.clickedButton}}
      @size="s"
      @fill={{true}}
      @color="danger"
    >
      Small Filled
    </EuiButton>
  </div>
</div>
<EuiSpacer @size="s" />
<EuiTitle @size="xs">
  Button as links
</EuiTitle>
<EuiSpacer @size="s" />
<div class="euiFlexGroup euiFlexGroup--gutterSmall euiFlexGroup--alignItemsCenter">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @href="http://www.elastic.co">
      Link to elastic.co
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonEmpty @isDisabled={{this.disabledLink}} @href="http://www.elastic.co">
      Link to elastic.co
    </EuiButtonEmpty>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @href="http://www.elastic.co" @iconType="link" aria-label="This is a link" />
  </div>
</div>
<EuiSpacer @size="s" />
<EuiTitle @size="xs">
  Button with Icon
</EuiTitle>
<EuiSpacer @size="s" />
<div class="euiFlexGroup euiFlexGroup--gutterSmall euiFlexGroup--alignItemsCenter">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @iconType="pencil" @onClick={{this.clickedButton}}>
      Primary
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @iconType="pencil" @fill={{true}} @iconSide="right" @onClick={{this.clickedButton}}>
      Primary
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <div class="euiFlexItem euiFlexItem--flexGrowZero">
      <EuiButton
        @iconType="pencil"
        @iconSide="right"
        @isDisabled={{true}}
        @onClick={{this.clickedButton}}
      >
        Disabled
      </EuiButton>
    </div>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <div class="euiFlexItem euiFlexItem--flexGrowZero">
      <EuiButton
        @iconType="pencil"
        @fill={{true}}
        @isDisabled={{true}}
        @onClick={{this.clickedButton}}
      >
        Disabled
      </EuiButton>
    </div>
  </div>
</div>
<EuiSpacer />
<EuiTitle @size="xs">
  Loading State
</EuiTitle>
<EuiSpacer @size="s" />
<div class="euiFlexGrid euiFlexGrid--responsive euiFlexGrid--fourths euiFlexGrid--gutterLarge">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @color="primary" @isLoading={{true}}>
      Loading...
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @color="primary" @isLoading={{true}} @fill={{true}}>
      Loading...
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @color="primary" @isLoading={{true}} @fill={{true}} @iconSide="right">
      Loading...
    </EuiButton>
  </div>
</div>
<EuiSpacer />
<EuiTitle @size="m">
  Button Empty
</EuiTitle>
<div class="euiFlexGrid euiFlexGrid--responsive euiFlexGrid--fourths euiFlexGrid--gutterLarge">
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonEmpty @color="primary">
      Primary
    </EuiButtonEmpty>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonEmpty @color="primary" @isLoading={{false}} @isDisabled={{true}}>
      Disabled
    </EuiButtonEmpty>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonEmpty @color="primary" @isLoading={{true}} @isDisabled={{false}}>
      Loading
    </EuiButtonEmpty>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonEmpty @color="primary" @iconSide="right" @isLoading={{true}} @isDisabled={{false}}>
      Loading Right
    </EuiButtonEmpty>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonEmpty @color="danger">
      Danger
    </EuiButtonEmpty>
  </div>
</div>
<EuiSpacer @size="l" />
<EuiTitle @size="m">
  Icon Button
</EuiTitle>
<div
  class="euiFlexGroup euiFlexGroup--directionRow euiFlexGroup--responsive euiFlexGroup--gutterLarge"
>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @color="primary" @iconType="arrowRight" @iconSize="s" />
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @color="text" @iconType="arrowRight" @iconSize="m" />
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @color="accent" @iconType="arrowRight" @iconSize="l" />
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @color="warning" @iconType="arrowRight" @iconSize="xl" />
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @color="danger" @iconType="arrowRight" @iconSize="xxl" />
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @color="ghost" @iconType="arrowRight" @iconSize="xxl" />
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @color="subdued" @iconType="arrowRight" @iconSize="xxl" />
  </div>
</div>
<div
  class="euiFlexGroup euiFlexGroup--directionRow euiFlexGroup--responsive euiFlexGroup--gutterLarge"
>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon
      @color="primary"
      @iconType="arrowRight"
      @iconSize="original"
      @onClick={{this.toggleIconButton}}
    />
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon @color="success" @iconType="arrowRight" @isDisabled={{true}} />
  </div>
</div>
<EuiSpacer />
<EuiTitle @size="m">
  Toggle Buttons
</EuiTitle>
<EuiSpacer />
<EuiCallOut
  @color="warning"
  @iconType="alert"
  @title="Do not add @aria-pressed or @isSelected if you also change the readable text."
/>
<EuiSpacer @size="xs" />
<div
  class="euiFlexGroup euiFlexGroup--directionRow euiFlexGroup--alignItemsCenter euiFlexGroup--gutterSmall"
>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton
      @isSelected={{this.button1On}}
      @fill={{this.button1On}}
      @iconType={{if this.button1On "stopFilled" "stop"}}
      @onClick={{fn this.toggleButtonState "button1On"}}
    >
      Toggle me
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButton @onClick={{fn this.toggleButtonState "button2On"}}>
      {{if this.button2On "I have changed!" "Click to change text!"}}
    </EuiButton>
  </div>
  <div class="euiFlexItem euiFlexItem--flexGrowZero">
    <EuiButtonIcon
      @title="Autosave"
      @iconType="save"
      aria-pressed={{this.button3On}}
      @color={{if this.button3On "primary" "subdued"}}
      @onClick={{fn this.toggleButtonState "button3On"}}
    />
  </div>
</div>
```

```js component
import Component from '@glimmer/component';
import { action } from '@ember/object';
import { tracked } from '@glimmer/tracking';

export default class Demo1ButtonComponent extends Component {

  @tracked selectedIconButton = false;
  @tracked button1On = false;
  @tracked button2On = false;
  @tracked button3On = false;

  @tracked disabledLink = false;

  @action
  toggleIconButton () {
    this.toggleProperty('selectedIconButton');
  }

  @action
  clickedButton () {
    alert('You clicked a button!');
  }

  @action
  toggleButtonState (btn) {
    this.toggleProperty(btn);
  }
}
```