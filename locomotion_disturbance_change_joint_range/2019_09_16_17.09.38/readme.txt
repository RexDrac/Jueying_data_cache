actor-layer-size: [256, 256]
gamma: 0.955
replay-start-size: 10000
gating-index: None
interpolation: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-index: None
critic-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
max-path-num: 20
actor-weight-decay: 1e-06
tau: 0.001
test-num: 4
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-train-time: 10
loss-output-bound-coeff: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
record-start-size: 10000.0
prioritized-exp-replay: True
max-test-time: 10
expert-num: 4
loss-output-diff-coeff: 0
max-step-num: 2500000000
n-step: 1
HLC-frequency: 25
loss-entropy-coeff: 0.0
filter-action: True
max-episode-num: 5000000
epoch-num: 500
imitation-weight: 0.5
reward-scale: 0.1
epoch-step-num: 5000000
total-step-num: 2500000000
rollout-step-num: 1
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
filter-torque: False
gating-layer-size: [32, 32]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
squash-action: True
train-step-num: 1
critic-lr: 0.0003
bullet-default-PD: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -1.884   0.6981
  -0.5236 -1.884   0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-buffer-size: 1000000
task-weight: 0.5
dsr-gait-period: 0.6
action-dim: 12
Physics-frequency: 1000
dsr-gait-freq: 1.667
max-path-step: 5000
actor-l2-reg: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
state-dim: 23
critic-activation-fn: ['relu', 'relu', 'None']
render-eval: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
critic-weight-decay: 1e-06
loss-output-smooth-coeff: 0.5
replay-ratio: 1
